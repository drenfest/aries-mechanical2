<script>
    import Hero from '../../components/Hero.svelte';
    import ProductGuide from '../../components/ProductGuide.svelte';
    import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>
</style>
<Hero
        heroImage="/assets/images/heros/hvacthero1.jpg"
        heroTitle="Save Money With Annual"
        heroBigText="Air Conditioner &amp; Furnace Maintenance"
        heroText="Maintain your Heating &amp; Cooling Appliances">
    <p>Be Prepared For Any Season &amp; Improve The Lifespan Of Your Air Conditioner Or Furnace With Annual Maintenance.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Annual Maintenance Now</a>
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
