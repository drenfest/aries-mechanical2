<script>
    import Hero from '../../components/Hero.svelte';
         import ProductGuide from '../../components/ProductGuide.svelte';
     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/achero1.jpg"
        heroTitle="Affordable & Quality"
        heroBigText="Air Conditioner Repair"
        heroText=" Your Top Rated A/C Repair Company">
    <p>Our trained and certified specialists have the expertise and knowledge to guide you into total home cooling. </p>
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
