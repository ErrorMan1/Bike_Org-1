<template>
<v-app dark>
    <v-container >
        <section>
            <v-carousel>
                <v-carousel-item
                    v-for="(item,i) in items"
                    :key="i"
                    :src="item.src">
                </v-carousel-item>
            </v-carousel>
        <span></span>
        <span></span>
        <span></span>
        <v-layout wrap align-center>
            <v-flex xs12>
                <v-container grid-list-xl>
                    <v-layout align-space-around justify-center column reverse>
                        <v-card class="elevation-1">
                            <v-flax xs4>
                                <h2>University of Phayao Game</h2>
                                <img src="http://www.up.ac.th/FileUpload/0fupcjxb.jpg" alt="Vuetify.js" height="150">
                            </v-flax>
                            <v-card-text>
                            เป็นปีแรกที่ มหาวิทยาลัยพะเยาเข้าแข่งขันกีฬาจักรยาน โดยเป็นไปตามคาดได้รับเหรียญทองจากจักรยานเสือภูเขา 1 เหรียญ 
                            และจากจักรยานเสือหมอบ 2 เหรียญ
                            </v-card-text>
                            <v-btn left bottom color="blue" @click="dialog = !dialog">สมัครเข้าร่วมรายการ</v-btn>
                        </v-card>
                        <br>
                        <v-card class="elevation-1">
                            <br>
                            <v-flax xs4>
                                <h2>University of Phayao Game</h2>
                                <img src="http://www.up.ac.th/FileUpload/0fupcjxb.jpg" alt="Vuetify.js" height="150">
                                
                            </v-flax>
                            <v-card-text>
                            เป็นปีแรกที่ มหาวิทยาลัยพะเยาเข้าแข่งขันกีฬาจักรยาน โดยเป็นไปตามคาดได้รับเหรียญทองจากจักรยานเสือภูเขา 1 เหรียญ 
                            และจากจักรยานเสือหมอบ 2 เหรียญ
                            </v-card-text>
                            <v-btn left bottom color="blue" @click="dialog = !dialog">สมัครเข้าร่วมรายการ</v-btn>
                        </v-card>
                        <br>
                        <v-card class="elevation-1">
                            <br>
                            <v-flax xs4>
                                <h2>University of Phayao Game</h2>
                                <img src="http://www.up.ac.th/FileUpload/0fupcjxb.jpg" alt="Vuetify.js" height="150">
                                
                            </v-flax>
                            <v-card-text>
                            เป็นปีแรกที่ มหาวิทยาลัยพะเยาเข้าแข่งขันกีฬาจักรยาน โดยเป็นไปตามคาดได้รับเหรียญทองจากจักรยานเสือภูเขา 1 เหรียญ 
                            และจากจักรยานเสือหมอบ 2 เหรียญ
                            </v-card-text>
                            <v-btn left bottom color="blue" @click="dialog = !dialog">สมัครเข้าร่วมรายการ</v-btn>
                        </v-card>
                    </v-layout>
                    <!-- Modal -->
                    <v-dialog v-model="dialog" width="1000px">
                        <v-card>
                            <v-card-title
                            class="dark lighten-4 py-4 title"
                            >
                            Create contact
                            </v-card-title>
                            <v-container grid-list-sm class="pa-4">
                            <v-layout row wrap>
                                <v-flex xs12 align-center justify-space-between>
                                <v-layout align-center>
                                    <v-avatar size="40px" class="mr-3">
                                    <img
                                        src="//ssl.gstatic.com/s2/oz/images/sge/grey_silhouette.png"
                                        alt=""
                                    >
                                    </v-avatar>
                                    <v-text-field
                                    placeholder="Name"
                                    ></v-text-field>
                                </v-layout>
                                </v-flex>
                                <v-flex xs6>
                                <v-text-field
                                    prepend-icon="business"
                                    placeholder="Company"
                                ></v-text-field>
                                </v-flex>
                                <v-flex xs6>
                                <v-text-field
                                    placeholder="Job title"
                                ></v-text-field>
                                </v-flex>
                                <v-flex xs12>
                                <v-text-field
                                    prepend-icon="mail"
                                    placeholder="Email"
                                ></v-text-field>
                                </v-flex>
                                <v-flex xs12>
                                <v-text-field
                                    type="tel"
                                    prepend-icon="phone"
                                    placeholder="(000) 000 - 0000"
                                    mask="phone"
                                ></v-text-field>
                                </v-flex>
                                <v-flex xs12>
                                <v-text-field
                                    prepend-icon="notes"
                                    placeholder="Notes"
                                ></v-text-field>
                                </v-flex>
                            </v-layout>
                            </v-container>
                            <v-card-actions>
                            <v-spacer></v-spacer>
                            <v-btn flat color="primary" @click="dialog = false">Cancel</v-btn>
                            <v-btn flat @click="dialog = false">Save</v-btn>
                            </v-card-actions>
                        </v-card>
                    </v-dialog>
                    <!-- End Modal -->
                </v-container>
            </v-flex>
        </v-layout>
        </section>
    </v-container>
</v-app>
</template>

<script>
  export default {
    data: () => ({
        dialog: false,
        items: [
          {
            src: 'https://tiewtiddin.com/wp-content/uploads/2018/05/%E0%B8%A1%E0%B8%AB%E0%B8%81%E0%B8%A3%E0%B8%A3%E0%B8%A1%E0%B8%88%E0%B8%B1%E0%B8%81%E0%B8%A3%E0%B8%A2%E0%B8%B2%E0%B8%99%E0%B8%97%E0%B8%B2%E0%B8%87%E0%B9%84%E0%B8%81%E0%B8%A5-2561-1-627x355.jpg'
          },
          {
            src: 'https://i.ytimg.com/vi/biFAqxjFxgg/maxresdefault.jpg'
          },
          {
            src: 'http://thaibike.org/wp-content/uploads/2016/11/y2z848.jpg'
          }
        ]
    }),
  };
</script>