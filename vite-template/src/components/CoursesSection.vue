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
                <div class="col-5">
                    <div class="card py-4 px-1">
                        <img src="../assets/new-corner.jpg" alt="">
                        <div class="card-body text-center">
                            <h5 class="card-title p-2">Courses</h5>
                            <h6 class="card-subtitle text-center py-5 px-3 text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel voluptates omnis voluptatem asperiores, reprehenderit autem quam repellat illo accusantium reiciendis veniam corrupti alias nulla officiis! Iusto sint tenetur deserunt odit.</h6>
                            <button @hover="" type="submit" class="mybtn text-center">COURSE INFORMATION</button>
                        </div>
                    </div>
                </div>
                <div class="col-7 p-5">
                    <div class="container-fluid">
                        <div class="courses-services row">
                            <div class="col-4">
                                <div class="course-card">
                                    <img src="../assets/courses-passplus-200x200.jpg" class="card-img-top" alt="...">
                                    <div class="card-body text-center">
                                        <h5 class="card-title py-3">Pass Plus</h5>
                                        <a href="#" class="my-btn btn-primary py-2">LEARN MORE</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-4">
                                <div class="course-card">
                                    <img src="../assets/course-intensive-200x200.jpg" class="card-img-top" alt="...">
                                    <div class="card-body text-center">
                                        <h5 class="card-title py-3">Intensive Course</h5>
                                        <a href="#" class="my-btn btn-primary py-2">LEARN MORE</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-4">
                                <div class="course-card">
                                    <img src="../assets/courses-instructor-200x200.jpg" class="card-img-top" alt="...">
                                    <div class="card-body text-center">
                                        <h5 class="card-title py-3">Instructors</h5>
                                        <a href="#" class="my-btn btn-primary py-2">LEARN MORE</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="card">
                        <div class="percentage-card py-3">
                            <div class="flex-wrapper justify-content-center">
                                <div class="single-chart p-5">
                                    <svg viewBox="0 0 36 36" class="circular-chart green">
                                    <path class="circle-bg"
                                        d="M18 2.0845
                                        a 15.9155 15.9155 0 0 1 0 31.831
                                        a 15.9155 15.9155 0 0 1 0 -31.831"
                                    />
                                    <path class="circle"
                                        stroke-dasharray="93, 100"
                                        d="M18 2.0845
                                        a 15.9155 15.9155 0 0 1 0 31.831
                                        a 15.9155 15.9155 0 0 1 0 -31.831"
                                    />
                                    <text x="18" y="20.35" class="percentage">95%</text>
                                    </svg>
                                </div>
                            
                            </div>
                        
                            <div class="card-body text-center">
                                <h5 class="card-title py-3">PASS RATE</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="card">
                        <div class="percentage-card py-3">
                            <div class="flex-wrapper justify-content-center">
                                <div class="single-chart p-5">
                                    <svg viewBox="0 0 36 36" class="circular-chart green">
                                    <path class="circle-bg"
                                        d="M18 2.0845
                                        a 15.9155 15.9155 0 0 1 0 31.831
                                        a 15.9155 15.9155 0 0 1 0 -31.831"
                                    />
                                    <path class="circle"
                                        stroke-dasharray="100, 100"
                                        d="M18 2.0845
                                        a 15.9155 15.9155 0 0 1 0 31.831
                                        a 15.9155 15.9155 0 0 1 0 -31.831"
                                    />
                                    <text x="18" y="20.35" class="percentage">100%</text>
                                    </svg>
                                </div>
                            
                            </div>
                            
                            <div class="card-body text-center">
                                <h5 class="card-title py-3">REFERRAL RATE</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="card">
                        <div class="percentage-card py-3">
                            <div class="flex-wrapper justify-content-center">
                                <div class="single-chart p-5">
                                    <svg viewBox="0 0 36 36" class="circular-chart green">
                                    <path class="circle-bg"
                                        d="M18 2.0845
                                        a 15.9155 15.9155 0 0 1 0 31.831
                                        a 15.9155 15.9155 0 0 1 0 -31.831"
                                    />
                                    <path class="circle"
                                        stroke-dasharray="2, 100"
                                        d="M18 2.0845
                                        a 15.9155 15.9155 0 0 1 0 31.831
                                        a 15.9155 15.9155 0 0 1 0 -31.831"
                                    />
                                    <text x="18" y="20.35" class="percentage">0%</text>
                                    </svg>
                                </div>
                            
                            </div>
                    
                            <div class="card-body text-center">
                                <h5 class="card-title py-3">ACCIDENT RATE</h5>
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
    background-image: url('../assets/promise-background.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position-y: -400px;
    .new-courses{
        .col-5{
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
            img {
                position: absolute;
                top: 0;
                left: 0;
                width: 20%;
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
	font-size:14px;
	padding:14px 48px;
	text-decoration:none;
	text-shadow:0px 0px 2px #2f6627;
    }
    .my-btn:hover {
        background-color:#7799ad;
        color: white;

    }
    .my-btn:active {
        position:relative;
        top:1px;
    }

    .course-card .card-title {
        color: #7799ad;
        font-size: 24px;
    }
    .card-subtitle {
        line-height: 40px;
    }   
    /*
    PROVA
    */
    .flex-wrapper {
        display: flex;
        flex-flow: row nowrap;
    }

    .single-chart {
        width: 100%;
        justify-content: space-around ;
    }

    .circular-chart {
        display: block;
        margin: 10px auto;
        max-width: 80%;
        max-height: 250px;
    }

    .circle-bg {
        fill: none;
        stroke: #eee;
        stroke-width: 1.8;
    }

    .circle {
        fill: none;
        stroke-width: 1.8;
        stroke-linecap: round;
        animation: progress 1s ease-out forwards;
    }

    @keyframes progress {
        0% {
            stroke-dasharray: 0 100;
        }
    }

    .circular-chart.orange .circle {
        stroke: #ff9f00;
    }

    .circular-chart.green .circle {
        stroke: #7abc64;
    }

    .circular-chart.blue .circle {
        stroke: #3c9ee5;
    }

    .percentage {
        fill: #929aa3;
        font-family: sans-serif;
        font-size: 0.5em;
        font-weight: 100;
        text-anchor: middle;
    }
    .percentage-card {
        border-top: 6px solid #7abc64;

    }
    .percentage-card .card-title{
       font-size: 18px;
       font-weight: 300;
       color:#929aa3 ;
    }
}
</style>