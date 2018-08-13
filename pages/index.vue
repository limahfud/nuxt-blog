<template>
    <div class="homepage">
        <section class="intro">
            <h1>Welcome to my blogs</h1>
        </section>

        <section class="featured-posts">
            <div class="posts">
                <ul>
                    <li>
                        <nuxt-link :to="'/posts/' + 1">
                            <article class="post-preview">
                                <div class="post-thumbnail">
                                    <img src="https://courses.telegraph.co.uk/images/26/625x351/coding625x351.jpg" alt="">
                                </div>
                                <div class="post-content">
                                    <h1>2018, Indonesian Market Going Up</h1>
                                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Veritatis atque exercitationem cum illo tempora quo, consequatur dolorum. Esse, ducimus assumenda eaque placeat laboriosam itaque quasi doloribus obcaecati beatae. Tenetur, neque?</p>
                                </div>
                            </article>
                        </nuxt-link>
                    </li>
                    <li>
                        <nuxt-link :to="'/posts/' + 1">
                            <article class="post-preview">
                                <div class="post-thumbnail">
                                    <img src="http://teachmag.com/wp-content/uploads/2015/06/CodeBreakers_636x362_b.jpg" alt="">
                                </div>
                                <div class="post-content">
                                    <h1>Why You Should Hire Anyone</h1>
                                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam ullam accusamus, repudiandae tempora nisi, assumenda expedita consectetur officiis, obcaecati earum doloribus sint unde iste iure ducimus eaque voluptate omnis consequuntur!</p>
                                </div>
                            </article>
                        </nuxt-link>
                    </li>
                </ul>
            </div>
        </section>
    </div>
</template>

<style scoped>
    .intro {
        margin: 0;
        padding: 0;
        width: 100%;
        min-height: 150px;
        background: #224422;
        color: white;
    }

    .intro h1 {
        font-size: 20px;
        font-weight: 400;
        display: block;
        margin: auto;
        text-align: center;
        line-height: 150px;
    }

    .posts ul {
        padding: 0;
        margin: 10px;

    }

    .posts ul li{
        margin-bottom: 10px;
        list-style: none;
        border: solid 1px #ababab;
        border-radius: 10px;
        overflow: hidden;
        border: none;
        -webkit-box-shadow: 4px 4px 10px 0px rgba(204,204,204,0.43);
        -moz-box-shadow: 4px 4px 10px 0px rgba(204,204,204,0.43);
        box-shadow: 4px 4px 10px 0px rgba(204,204,204,0.43);
    }

    .posts ul li a {
        border-radius: 10px;
        text-decoration: none;
        color: #898899;
        box-shadow: #224422;
    }

    .post-preview * {
        color: #555555;
        font-weight: 400;
    }

    .post-thumbnail {
        margin: 0;
        padding: 0;
    }

    .post-thumbnail img {
        width: 100%;
    }

    .post-content {
        padding: 5px;
    }

    .post-content p {
        color: #888888;
        margin-top: 10px;
        font-size: 12px;
    }
</style>

