<script>
import Header from "../../lib/Header.svelte";
    import Footer from "../../lib/Footer.svelte";
</script>
<Header headingTitle = "Contact"/>
<section><ul>
    <li>
        <label>Name: </label><input type="text" name="Name" id="name">
    </li>
    <li>
        <label>Email: </label><input type="email" name="email" id="email">
    </li>
    <li>
        <label>Your Message: </label><input type="text" name="Message" id="message">
    </li>
</ul></section>
<Footer />
<style></style>