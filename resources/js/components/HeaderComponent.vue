<template>
    <div>
        <body>
        <header>
                <h1>
                    <a href="/">One Tab CoLoFul</a><br>
                </h1>
                <nav class="pc-nav">
                    <ul>
                        <li><router-link to="/tasks">タブ一覧</router-link></li>
                        <li><router-link to="/tasks/create">新規作成</router-link></li>
                    </ul>
                </nav>
            </header>
        </body>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
header {
padding: 32px 4% 0px;
position: fixed;
top: 0;
width: 100%;
background-color: transparent;
display: flex;
align-items: center;
z-index: 2;
}
h1 {
margin: 0; padding: 0;
font-size: 24px;
color: #FF8C00;
background: -webkit-linear-gradient(0deg, #40E0D0, #FF8C00, #FF0080);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
}

router-link{
    text-decoration: none;
}

li{	
text-decoration: none;
color: #FF8C00;
background: -webkit-linear-gradient(0deg, #40E0D0, #FF8C00, #FF0080);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
}
h1{	
text-decoration: none;
color: #FF8C00;
background: -webkit-linear-gradient(0deg, #40E0D0, #FF8C00, #FF0080);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
}

nav {
margin: 0 0 0 auto;
}
ul {
list-style: none;
margin: 0 auto;
display: flex;
margin-right: 130px;
font-weight: bold;
}
li {
margin: 0 0 0 15px;
font-size: 16px;
font-weight: bold;
}

/* スマホ対応 */
@media screen and (max-width: 479px) { /*ウィンドウ幅が最大479pxまでの場合に適用*/
body{
overflow:hidden;
}


header {
padding: 30px 4% 10px;
position: fixed;
top: 0;
width: 100%;
background-color: transparent;
display: flex;
align-items: center;
z-index: 2;
}

h1{
margin: 0; padding: 0;
font-size: 16px;
}

ul{
list-style: none;
display: flex;
margin-right: 30px;
font-weight: bold;
}

li{
font-size: 12px;
}
}
</style>