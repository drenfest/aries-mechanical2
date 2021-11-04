<script>
    import Hero from '../../components/Hero.svelte';
     import ProductGuide from '../../components/ProductGuide.svelte';
     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/hmhero1.jpg"
        heroTitle="Affordable and High Quality"
        heroBigText="Air Conditioner Cleaning Services"
        heroText=" Your Top Rated A/C Cleaning Company">
    <p>Aries Mechanical technicians are professional certified to install, clean and repair the latest air cleaning technology.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <ProductGuide/>
            <SidebarSubnav />
        </aside>
    </div>
</div>
