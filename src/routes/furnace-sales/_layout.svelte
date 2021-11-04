<script>
    import Hero from '../../components/Hero.svelte';
 import ProductGuide from '../../components/ProductGuide.svelte';
     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/hmhero1.jpg"
        heroTitle="Affordable & Quality HVAC Services"
        heroBigText="New Furnace Installation"
        heroText=" Your New Furnace Installation & Repair Company">
    <p>New Furnace Installation Newark, Oswego, Plano, Sandwich, Yorkville, for upgraded of efficiency, to transform your Comfort. </p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <SidebarSubnav />
            <ProductGuide/>

        </aside>
    </div>
</div>
