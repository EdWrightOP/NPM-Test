<script>
    export let headingTitle;
   
</script>

<header>
<h1>{headingTitle}</h1>
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/">About</a></li>
            <li><a href="/">Contact</a></li>
        </ul>
    </nav>
</header>

<style>
h1{
    display: flex;
    justify-content: start;
}
ul{
    display: flex;
    justify-content: space-around;
    list-style: none;

}
li a{
    font-style: normal;
    text-decoration: none;
    color: #333;
}
</style>