<template>
<div class="main">
    <h1>Abount Me</h1>
    <div class="box">
        <div class="row">
            <div class="box-4u">
                <div class="ico">
                    <img src="../assets/top_ico.png" alt="blog" />
                </div>
            </div>
            <div class="box-8u">
                <div>
                    <h3>名前:</h3>
                        Shotaro Takahashi
                </div>
            <div>
                <h3>趣味:</h3>
                    ゲーム / DTM / プログラミング
                </div>
            </div>
        </div>
        <div class="row">
            <div class="box-4u">
                <a href="https://note.milldea.com/author/shotaro" target="_blank" rel="noopener noreferrer">
                    <div class="image">
                        <img src="../assets/top_blog.jpg" alt="blog" />
                    </div>
                    <p class="image_txt">Blog</p>
                </a>
            </div>
            <div class="box-4u">
                <a href="https://github.com/milldea-takahashi" target="_blank" rel="noopener noreferrer">
                    <div class="image">
                        <img src="../assets/top_github.png" alt="github" />
                    </div>
                    <p class="image_txt">GitHub</p>
                </a>
            </div>
        </div>
    </div>
    <div class="footer">
        GitHub Pagesで公開しています。
    </div>
</div>
</template>
<script>
export default {
  name: "topPage",
};
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Zen+Kaku+Gothic+New&display=swap');

h1{
    font-size: 2em;
    text-align: center;
}

h2{
    font-size: 1.75em;
    text-align: center;
}
h3{
    font-size: 1.25em;
    margin: 1em 0 0 0;
}
a{
    text-decoration: none;
    color: inherit;
}
img{
    width: 100%;
}
.main{
    font-family: 'Zen Kaku Gothic New', sans-serif;
    font-size: 16px;
    overflow-wrap: break-word
}
.box{
    width: clamp(100px,90%,100vh);
    margin-left: auto;
    margin-right: auto;
    text-align: left;
}
.row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    width: 100%;
    margin-left: auto;
    margin-right: auto;
}
.box-4u{
    width: clamp(15vh,20%,100vh);
    height: 100%;
    margin: 2%;
}
.box-8u{
    width: clamp(15vh,40%,100vh);
    height: 100%;
    margin: 2%;
}
.image{
    width: 90%;
    height: 90%;
    margin: 5%;
}
.image:hover{
    width: 100%;
    height: 100%;
    margin: 0%;
}
.image_txt{
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    text-align: center;
    margin: 0;
}
.footer{
    text-align: center;
    margin-top: 2em;
    margin-bottom: 2em;
}
</style>