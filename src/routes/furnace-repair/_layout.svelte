<script>
    import Hero from '../../components/Hero.svelte';
    import ProductGuide from '../../components/ProductGuide.svelte';
     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>

</style>
<Hero heroImage="/assets/images/heros/heathero1.jpg"
      heroTitle="High Quality & Affordable Furnace Repair & Installation Services"
      heroBigText="Furnace Repair"
      heroText="We are here to answer any questions you may have.">
    <p>Furnace Repair Services Newark, Plano, Sandwich, Yorkville, Oswego IL  Throughout Chicagoland area cold weather can come upon us within 24 hours.</p>
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
