<svetle:head> 
<title>black mamba<title>
</svetle:head>

<div class="container">
    <div class="info">
        <div class="animate-background">
            <div class="container info-container">
                <div class="info-text">
                    <h1>
                        <p class="animate-text-1">Lorem ipsum dolor sit amet.</p>
                        <p class="text-2">Lorem ipsum dolor sit amet consectetur.</p>
                    </h1>
                </div>
                <h2 class="subtitle">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa delectus molestias at esse itaque dolorem?
                </h2>
                <div style="color: black;" class="scroll-button animate-scroll" tabindex="-1">
                    <a href="/about">Click here</a>
                    <div class="arrow">→</div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="background-div"></div>
<style>
.info {
    text-align: left;
}

.info-container {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    text-align: left;
    align-items: flex-start;
}

.container {
    max-width: 1400px;
    margin: 100px 0 0 2.5rem;
	margin-top: 200px;
}

.info h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.info h1 p {
    font: inherit;
    margin: 0;
    text-align: left;
    line-height: 120%;
    font-weight: 600;
}

.info h2 {
    max-width: 60ch;
    font-weight: 400;
    margin-top: 0.30rem;
}

.background-div {
    background-color: #f0f0f0;
    height: 50vh;
    margin: 0 auto;
}

.scroll-button {
    display: inline-block;
    background-color: #4285F4;
    color: white;
    padding: 5px 10px;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 20px;
}

.scroll-button .arrow {
    margin-left: 5px;
}
</style>
