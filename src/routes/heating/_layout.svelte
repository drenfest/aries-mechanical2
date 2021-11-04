<script>
    import Hero from '../../components/Hero.svelte';
    import ProductGuide from '../../components/ProductGuide.svelte';
     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/heathero2.jpg"
        heroTitle="Affordable & High Quality"
        heroBigText="Heating Installation and Repair Services"
        heroText=" Your Furnace Installation & Furnace Repair Company">
    <p>Winter time in the Chicago Suburbs can be bone chilling cold. When winter cold settles in, heating your home isn't a luxury, it's a necessity.</p>
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
