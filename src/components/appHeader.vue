<template>
    <header class="header-container">
        <div class="left-section">
            <a href="#"><img src="../assets/img/logo.svg" alt=""></a>
        </div>
        <div class="menu">
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/pages">Pages</a></li>
                <li><a href="/mission">Our mission</a></li>
            </ul>
        </div>
        <div class="right-section">
            <div class="sign-in">
                <i class="fa fa-sign-in" aria-hidden="true"></i>
                <a href="#">Sign in</a>
            </div>
            <div class="sign-up">
                <i class="fa fa-sign-in" aria-hidden="true"></i>
                <a href="#">Sign up</a>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: "appHeader",
    props: {
        msg: String
    }
}
</script>

<style scoped lang="scss">
    .header-container {
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        z-index: 10;
        height: 70px;
        padding: 0 30px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: rgba($color: #222, $alpha: .7);
        .left-section {
            img {
                width: 50px;
            }
        }
        .menu {
            ul {
                display: flex;
                li {
                    list-style: none;
                    
                    a {
                        color: white;
                        text-decoration: none;
                        margin: 0 10px;
                        font-size: 18px;    
                        transition: all .3s ease;                
                    }
                    :hover {
                        color: #11AB7C;
                    }    
                }
            }
        }
        .right-section {
            display: flex;            
            .sign-in {
                background-color: #11AB7C;
                margin-right: 10px; 
                padding: 0 5px;
                transition: all .2s ease;
                a {                
                font-size: 17px;
                color: white;                
                text-decoration: none;                
                }
                i {
                    color: #fff;
                    margin-right: 5px;
                }
                &:hover {
                    transform: translate(0, -2px);
                }
            }
            .sign-up {
                transition: all .2s ease;
                background-color: #11AB7C;
                padding: 0 5px;
                a {                
                font-size: 17px;
                color: white;                
                text-decoration: none; 
                              
                }
                i {
                    color: #fff;
                    margin-right: 5px;
                }
                &:hover {
                    transform: translate(0, -2px);
                }
            }
        }
    }
</style>