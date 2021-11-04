<script>
    import Hero from '../../components/Hero.svelte';
    import ProductGuide from '../../components/ProductGuide.svelte';
    import SidebarSubnav from '../../components/SidebarSubnav.svelte';
    export let segment;
</script>
<style>
    .address{
        padding:2rem;
    }
</style>
<Hero
        heroImage="/assets/images/heros/hmhero1.jpg"
        heroTitle="Affordable & High Quality HVAC Services For Over 30 Years"
        heroBigText="Contact Aries Mechanical"
        heroText=" Fill Out The Form Below Or Call To Contact Aries">
    <p>Contact Aries Mechanical, Inc. at 815-695-5828. We are located at 101 East Taylor Street in Newark, IL 60541</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <div class="address">
                <h2>Contact Info</h2>
                <strong>Address: </strong>
                <address>
                    101 East Taylor Street
                    Newark, IL 60541
                </address>
                <strong>Phone: </strong><a href="tel:+1815-695-5828">815.695.5828</a><br>
                <strong>Email: </strong><a href="mailto:steve@aries-mechanical.com">steve@aries-mechanical.com</a>
            </div>
            <SidebarSubnav {segment}/>
            <ProductGuide/>
        </aside>
    </div>
</div>
