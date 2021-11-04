<script>
    import Hero from '../../components/Hero.svelte';
    import ProductGuide from '../../components/ProductGuide.svelte';
     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/achero3.jpg"
        heroTitle="Affordable & High Quality"
        heroBigText="New Air Conditioning Installation"
        heroText=" Your new Air Conditioner Repair Company">
    <p>Aries Mechanical $200 OFF any new furnace or A/C installation. Not to be combined with any other discount or offer</p>
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
