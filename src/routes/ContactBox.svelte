<script>
    import email from '$lib/images/logo/email.svg'
    import github from '$lib/images/logo/github.svg'
    import linkedin from '$lib/images/logo/linkedin.svg'
    import instagram from '$lib/images/logo/instagram.svg'
</script>

<div class="contact">
    <p class="title"> Contact Me By: </p>
    <p class="email">
        <img class="logo" src={email} alt="Email"/>
        hannahkhw@snu.ac.kr
    </p>
    <p class="linkedin"> 
        <img class="logo" src={linkedin} alt="LinkedIn"/>
         <a href="https://www.linkedin.com/in/kimheonningg/">https://www.linkedin.com/in/kimheonningg/</a>
    </p>
    <p class="github">
        <img class="logo" src={github} alt="GitHub"/>
        <a href="https://github.com/kimheonningg">https://github.com/kimheonningg</a>
    </p>
    <p class="instagram">
        <img class="logo" src={instagram} alt="Instagram"/>
        <a href="https://www.instagram.com/heonningg_/">https://www.instagram.com/heonningg_/</a>
    </p>
</div>

<style>
    .contact {
        text-align: left;
        align-self: flex-start;
    }

    .title {
        font-weight: 700;
        font-size: 20px;
    }

    .logo {
        width: 12px;
        height: 12px;
    }
</style>