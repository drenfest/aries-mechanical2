<script>
    import Hero from '../../components/Hero.svelte';
    import CouponSidebar from '../../components/CouponSidebar.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/hmhero1.jpg"
        heroTitle="Affordable & High Quality"
        heroBigText="HVAC Products"
        heroText="Trane Hvac Catalog">
    <p>Now installing a new line of high tech hvac products.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <CouponSidebar/>
        </aside>
    </div>
</div>
