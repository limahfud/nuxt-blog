<template>
    <div class="single-post-page">
        <section class="post">
            <h1>Title of The Post</h1>
            <div class="post-details">
                <div class="last-update">Updated at _____</div>
                <div class="author">Written by _____</div>
            </div>
            <p>Content of the posts flying vessel</p>
        </section>

        <section class="feedback">
            <p>Send feedback to our awesome domain at alimahfud@gmail.com</p>
        </section>
    </div>
</template>

<style scoped> 
.single-post-page {
    padding: 20px;
    text-align: center;
    font-weight: 400;
}

h1 {
    font-weight: 400;
    margin-bottom: 30px;
    color: #333333;
}

.post-details {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 12px;
}

.post-details > * {
    padding-left: 10px;
}

p {
    color: #777777;
}

.feedback {
    font-size: 12px;
    margin-top: 10px;
    color: #778899;
}
</style>
