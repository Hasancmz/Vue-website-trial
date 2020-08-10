<template>
    <footer class="footer">
        <div class="footer-container">
            <a href="#"><img style="width: 70px;height: 60px;" src="primary.svg" alt=""></a>
            <p>Leaf - Non Profit environmental Bootstrap 4 Theme</p>
            <ul>
                <li><a href="#">Themesberg</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">License</a></li>
                <li><a href="#">Documentation</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
            <span>© Themesberg 2020. All rights reserved.</span>
        </div>
    </footer>
</template>

<script>
export default {
    name: "appFooter",
}
</script>

<style lang="scss" scoped>
    .footer {
        background-color: #222;
        height: 250px;
        text-align: center;        
        p {
            color: #11ab7c;
            margin-top: 25px;
            font-size: 18px;
        }
        ul {
            display: flex;
            justify-content: center;
            margin-top: 40px;
            padding-bottom: 10px;
            border-bottom: 1px solid #6fa897;
            li {
                margin: 15px;   
                list-style: none;             
                a {
                    color: #fff;
                    font-size: 17px;
                    transition: all .2s ease;
                    text-decoration: none;
                    &:hover {
                        color: #11ab7c;
                    }
                }                        
            }        
        }
        span {
            font-size: 14px;
            color: #fff;
            position: relative;
            top: 30px;
        }
    }
</style>