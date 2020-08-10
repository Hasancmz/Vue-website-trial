<template>
    <div class="hero">        
        <div class="hero-container">                
            <div class="left">
                <h1>We safeguard the environment.</h1>
                <p>Over the past several decades, as the world has
                    increasingly warmed, so has its potential to burn.
                </p>            
                <a href="#">
                    <div class="left-btn">
                        <i class="fa fa-book" aria-hidden="true"></i>
                        <span>Our mission</span>
                    </div>
                </a>
                <a href="#">
                    <div class="right-btn">
                        <i class="fa fa-download" aria-hidden="true"></i>
                        <span>Download report</span>
                    </div>
                </a>                
            </div>
            <div class="right">
                <img src="../assets/img/forest.svg" alt="">
            </div>                
        </div>
        <div class="box-container">
            <div class="box-in">
                <div class="box">
                    <h6>Carbon Dioxide</h6>                        
                    <i class="fa fa-long-arrow-up" aria-hidden="true"></i>
                    <h2>412</h2>                        
                </div>
                <div class="box">
                    <h6>Carbon Dioxide</h6>                        
                    <i class="fa fa-long-arrow-up" aria-hidden="true"></i>
                    <h2>412</h2>                        
                </div>
                <div class="box">
                    <h6>Carbon Dioxide</h6>                        
                    <i class="fa fa-long-arrow-up" aria-hidden="true"></i>
                    <h2>412</h2>                                            
                </div>
                <div class="box">
                    <h6>Carbon Dioxide</h6>                        
                    <i class="fa fa-long-arrow-up" aria-hidden="true"></i>
                    <h2>412</h2>                 
                </div>                 
            </div>
        </div>
        <div class="text-container">
            <div class="text-middle">
                <div class="left-text">
                    <p>LEAF was created to provide policymakers with regular scientific assessments on climate change, its implications and potential future risks, as well as to put forward adaptation and mitigation options.</p>
                </div>
                <div class="right-text">
                    <p>Through its assessments, the LEAF determines the state of knowledge on climate change. It identifies where there is agreement in the scientific community on topics related to climate change, and where further research is needed. The reports are drafted and reviewed in several stages, thus guaranteeing objectivity and transparency. The LEAF does not conduct its own research.</p>
                    <p>LEAF reports are neutral, policy-relevant but not policy-prescriptive. The assessment reports are a key input into the international negotiations to tackle climate change.</p>
                </div>                   
            </div> 
            <div class="text-btn">
                <a href="#">
                    <i class="fa fa-book" aria-hidden="true"></i>
                    <span>Learn more about Leaf</span>
                </a>
            </div>
        </div>   
        <div class="info-container">
            <div class="text-info">
                <h2>What is Climate Change?</h2>
                <p>Climate change occurs when changes in Earth's climate system result in new <br> weather patterns that remain in place for an extended period of time.</p>
            </div>
            <div class="info-box">
                <div class="all-box">
                    <div class="table-top">
                        <div class="evidence"><span>Evidence</span></div>
                        <h5>How Do We Know?</h5>
                        <p>The Earth's climate has changed throughout history</p>
                    </div>
                    <img src="@/assets/img/causes.svg" style="width: 348px;height: 202px;" alt="">
                </div>
                <div class="all-box">
                    <div class="table-top">
                        <div class="evidence"><span>Evidence</span></div>
                        <h5>How Do We Know?</h5>
                        <p>The Earth's climate has changed throughout history</p>
                    </div>
                    <img src="@/assets/img/causes.svg" style="width: 348px;height: 202px;" alt="">
                </div>
                <div class="all-box">
                    <div class="table-top">
                        <div class="evidence"><span>Evidence</span></div>
                        <h5>How Do We Know?</h5>
                        <p>The Earth's climate has changed throughout history</p>
                    </div>
                    <img src="@/assets/img/causes.svg" style="width: 348px;height: 202px;" alt="">
                </div>
            </div>
        </div> 
        <div class="activities-container">
            <div class="top-text">
                <div class="activities">
                    <span>Our Activities</span>
                </div>
                <p>The main activity of the LEAF is the preparation of reports <br> assessing the state of knowledge of climate change.</p>
            </div>
        </div>
        <div class="card-container">
            <div class="card-style">
                <a href=""><img src="@/assets/img/activity1.jpg" alt="">
                    <div class="card-opacity1"></div>
                    <div class="card-body">
                        <span><i class="fa fa-circle-o-notch" aria-hidden="true"></i>Scoping Meeting</span>
                        <h4>Scoping meeting for the Synthesis Report of the Sixth Assessment Report</h4>   
                        <p><i class="fa fa-calendar" aria-hidden="true"></i>February 21, 2020</p>                              
                    </div>
                </a>     
                <a href=""><img src="@/assets/img/activity2.jpg" alt="">
                    <div class="card-opacity2"></div>
                    <div class="card-body">
                        <span><i class="fa fa-circle-o-notch" aria-hidden="true"></i>Scoping Meeting</span>
                        <h4>Scoping meeting for the Synthesis Report of the Sixth Assessment Report</h4>   
                        <p><i class="fa fa-calendar" aria-hidden="true"></i>February 21, 2020</p>                              
                    </div>
                </a>  
                <a href=""><img src="@/assets/img/activity3.jpg" alt="">
                    <div class="card-opacity3"></div>
                    <div class="card-body">
                        <span><i class="fa fa-circle-o-notch" aria-hidden="true"></i>Scoping Meeting</span>
                        <h4>Scoping meeting for the Synthesis Report of the Sixth Assessment Report</h4>   
                        <p><i class="fa fa-calendar" aria-hidden="true"></i>February 21, 2020</p>                              
                    </div>
                </a>                 
            </div>    
        </div>           
    </div>
</template>

<script>
export default {
    name: "appBody",
}
</script>

<style lang="scss" scoped>
    .hero {
        .hero-container {
            display: flex;
            max-width: 1200px;            
            margin: 0 auto;
            margin-top: 150px;
            .left {
                flex: 1;
                margin-top: 50px;
                h1 {
                    font-size: 38px;
                    font-weight: 500;
                }
                p {
                    font-size: 20px;
                    margin-top: 50px;
                    color: #666F82;
                    letter-spacing: 1.2px;
                }
                .left-btn {
                        display: inline-block;
                        border-radius: 5px;
                        background-color: #11AB7C;
                        margin-top: 50px;
                        transition: all .2s;
                        padding: 10px 20px;
                        i {  
                            margin-right: 5px; 
                            color: white;                           
                        }
                        span {                            
                            color: white;
                            font-size: 15px;                    
                        }
                        &:hover {
                            transform: translate(0,-2px);
                        }                        
                    }
                    .right-btn {
                        padding: 10px 20px;
                        margin-left: 20px;
                        display: inline-block;
                        background-color: #11AB7C;
                        transition: all .2s;
                        border-radius: 5px;
                        i {
                            color: #fff; 
                            margin-right: 5px;                           
                        }
                        span {
                            color: #fff;
                            font-size: 15px;
                        }
                        &:hover {                    
                            transform: translate(0,-2px);
                        }
                    }
                }
            .right {
                flex: 1;
                position: relative;
                img {
                    position: absolute;
                    right: 0px;
                    width: 40vw;
                    height: 30vw;
                }
            }
        }
        .box-container {
            margin-top: 250px;
            .box-in {            
                display: flex;
                justify-content: space-around;
                .box {
                    width: 276px;
                    height: 160px;
                    background-color: #deedf8;
                    border-radius: 5px;
                    text-align: center;
                    line-height: 50px;
                    border: 2px solid #F3F7FA;                                                    
                    h6 {
                        font-size: 16px;
                        color: #2A3F71;                        
                        font-weight: lighter;                       
                    }                    
                    i {  
                    font-size: 28px;
                    color: #FA5252;                   
                    }
                    h2 {
                        font-size: 40px;
                        font-weight: lighter;
                        color: #66799E;           
                    }                                                             
                }
            }
        }
        .text-container {
            max-width: 1200px;
            margin: 0 auto;
            .text-middle {
                display: flex;
                margin-top: 145px;
                .left-text {
                    flex: 1;
                    padding-right: 25px;
                    p{
                        font-size: 19px;
                        font-weight: 500;
                        line-height: 35px;
                        letter-spacing: 1px;
                        color: #2A3555;
                    }
                }
                .right-text {
                    flex: 1;
                    padding-left: 25px;
                    p {
                        line-height: 35px;
                        font-size: 19px;
                        color: #666F82;
                        opacity: .8;
                        font-weight: lighter;
                    }
                    :nth-child(2) { 
                        margin-top: 28px;
                    }
                }
            }
            .text-btn {
                margin-top: 80px;
                text-align: center; 
                transition: all .2s ease;              
                a {
                    padding: 10px 15px;
                    background-color: #11AB7C;
                    text-decoration: none;
                    
                    i {
                        margin-right: 10px;
                        color: white;
                    }
                    span {
                        color: white;
                    }
                }
                &:hover {                        
                    transform: translate(0,-2px);
                }
            } 
        }  
        .info-container { 
            background-color: #deedf8;  
            margin-top: 50px;                     
            .text-info {
                max-width: 1200px;
                margin: 0 auto;
                text-align: center;               
                h2 {
                    padding-top: 150px;
                    font-weight: lighter;
                    color: #2a354f;
                    font-size: 2.5rem;
                    text-align: center;
                    line-height: 1.4;
                    margin-bottom: 2rem;
                }
                p {
                    font-size: 1.25rem;
                    font-weight: lighter;
                    color: #66799e;
                    line-height: 1.6;
                    text-align: center;                   
                }
            }
            .info-box {
                display: flex;
                justify-content: space-between;   
                max-width: 1200px;
                margin: 0 auto;    
                margin-top: 300px;    
                .all-box {
                    position: relative;
                    top: -200px;
                    width: 348px;
                    height: 405px;
                    border-radius: 5px;
                    background-color: white;
                    transition: all .2s;
                    border: 2px solid #F3F7FA;
                    .table-top {                        
                        padding-left: 50px;
                        padding-top: 30px;
                        .evidence {
                            width: 64px;
                            height: 23px;
                            background-color: #005AD4;
                            border-radius: 10rem;
                            text-align: center;
                            line-height: 1;                                                    
                            span {
                            
                                font-size: 11px;
                                color: white;
                                font-weight: bold;
                            }
                        }                        
                        h5 {
                            font-size: 1.25rem;
                            font-weight: lighter;
                            line-height: 1.4;
                            margin-top: 20px;
                        }
                        p {
                            color: #66799e;
                            font-size: 1rem;
                            font-weight: 300;
                            line-height: 1.6;
                            margin-top: 20px;
                        }
                    }                                    
                    img {
                        margin-top: 30px;                        
                    }
                    &:hover {
                        transform: translate(0,-4px);
                    }
                }
            }
        }
        .activities-container {
            margin: 120px 0;
            .activities {
                position: relative;
                width: 130px;
                height: 28px;
                background-color: #11AB7C;
                border-radius: 10rem;
                left: 50%;
                transform: translate(-50%);
                span {
                    color: white;
                    font-size: 15px;
                    height: 28px;
                    display: flex;
                    justify-content: center;
                    align-items: center;                    
                }
            }
            p {
                font-size: 2rem;
                font-weight: 500;
                line-height: 1.4;
                text-align: center;
                margin-top: 30px;
            }
        }    
        .card-container {
            max-width: 1200px;
            margin: 0 auto;
            .card-style {               
                display: flex;
                justify-content: space-between; 
                margin-bottom: 120px;                   
                a {
                    display: flex;
                    position: relative;
                    transition: all .2s;
                    img {
                        
                        width: 350px;
                        height: 558px;
                        background-color: white;
                        border-radius: 8px;
                        position: relative;
                        z-index: -1;
                    }                    
                    .card-opacity1 {
                        position: absolute;
                        width: 350px;
                        height: 558px;
                        border-radius: 8px;
                        background-color: #11ab7c;
                        opacity: .7;
                        z-index: 0;
                    }
                    .card-opacity2 {
                        position: absolute;
                        width: 350px;
                        height: 558px;
                        border-radius: 8px;
                        background-color: #005ad4;
                        opacity: .7;
                        z-index: 0;
                    }
                    .card-opacity3 {
                        position: absolute;
                        width: 350px;
                        height: 558px;
                        border-radius: 8px;
                        background-color: #de6926;
                        opacity: .7;
                        z-index: 0;
                    }                   
                    &:hover {
                        transform: translate(0,-3px);
                    }
                    .card-body {
                        position: absolute;
                        z-index: 1;
                        padding: 30px;
                        color: white;
                        span {
                            font-weight: 500;
                            font-size: 15px;                                                   
                            i {
                                margin-right: 20px;
                                margin-bottom: 40px;
                            }
                        }
                        h4 {
                            font-size: 1.5rem;
                            line-height: 1.4;
                            font-weight: lighter;
                            margin-bottom: 30px;
                        }
                        p {
                            i {
                                margin-right: 20px;
                            }
                        }
                    }
                }
            }
        }     
    }
</style>