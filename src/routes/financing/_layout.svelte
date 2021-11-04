<script>
    import Hero from '../../components/Hero.svelte';
    import ProductGuide from '../../components/ProductGuide.svelte';
    import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>
</style>
<Hero
        heroImage="/assets/images/heros/achero1.jpg"
        heroTitle="We Offer"
        heroBigText="Financing"
        heroText="Maintain your Heating &amp; Cooling Appliances">
    <p>Aries Mechanical Inc has teamed up with FTL offering financing solutions for customers who prefer not to get a home equity loan.</p>
    <a class="btn btn-light" href="/contact" title="Call Us Now To Get Started">Call Us Now To Get Started</a>
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
