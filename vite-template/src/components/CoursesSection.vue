<script>
export default {
    name: 'CoursesSection',
    components: {

    },
    defineProps :{
        //msg: String
    },
    data(){
        return {
            //
        }
    },


}
</script>

<template>
    <section>
        <div class="container">
            <div class="new-courses row justify-content-between py-5">
                <div class="col-4">
                    <div class="card py-4 px-1">
                        <div class="card-body text-center">
                            <h5 class="card-title p-2">Courses</h5>
                            <h6 class="card-subtitle text-center py-5 px-3 text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel voluptates omnis voluptatem asperiores, reprehenderit autem quam repellat illo accusantium reiciendis veniam corrupti alias nulla officiis! Iusto sint tenetur deserunt odit.</h6>
                            <button @hover="" type="submit" class="mybtn text-center">COURSE INFORMATION</button>
                        </div>
                    </div>
                </div>
                <div class="col-8">
                    <div class="container-fluid">
                        <div class="courses-services row">
                            <div class="col-4">
                                <div class="course-card">
                                    <img src="../assets/courses-passplus-200x200.jpg" class="card-img-top" alt="...">
                                    <div class="card-body text-center">
                                        <h5 class="card-title py-3">Pass Plus</h5>
                                        <a href="#" class="my-btn btn-primary py-2">Go somewhere</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-4">
                                <div class="course-card">
                                    <img src="../assets/course-intensive-200x200.jpg" class="card-img-top" alt="...">
                                    <div class="card-body text-center">
                                        <h5 class="card-title py-3">Intensive Course</h5>
                                        <a href="#" class="my-btn btn-primary py-2">Go somewhere</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-4">
                                <div class="course-card">
                                    <img src="../assets/courses-instructor-200x200.jpg" class="card-img-top" alt="...">
                                    <div class="card-body text-center">
                                        <h5 class="card-title py-3">Instructors</h5>
                                        <a href="#" class="my-btn btn-primary py-2">Go somewhere</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>
</template>

<style lang="scss" scoped>
section {

    .new-courses{
        .col-4{
            .card {
                position: relative;
                top: -80px;
                z-index: 1000;
                -webkit-box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68); 
                box-shadow: 0px 13px 15px 8px rgba(0,0,0,0.68);
                .mybtn {
                background-color:#7abc64;
                border-radius:23px;
                border:2px solid #7abc64;
                display:inline-block;
                cursor:pointer;
                color:#ffffff;
                font-family:Arial;
                font-size:18px;
                padding:14px 48px;
                text-decoration:none;
                text-shadow:0px 0px 2px #2f6627;
                }
                .mybtn:hover {
                    background-color:#ffffff;
                    color: #7abc64;
                }
                .mybtn:active {
                    position:relative;
                    top:1px;
                }
                h5 {
                    font-size: 40px;
                }
            }

        }

    }
    .my-btn {
	background-color:#ffffff;
	border-radius:23px;
	border:2px solid #7799ad;
	display:inline-block;
	cursor:pointer;
	color:#7799ad;
	font-family:Arial;
	font-size:18px;
	padding:14px 48px;
	text-decoration:none;
	text-shadow:0px 0px 2px #2f6627;
    }
    .my-btn:hover {
        background-color:#7799ad;
    }
    .my-btn:active {
        position:relative;
        top:1px;
    }

        
}
</style>