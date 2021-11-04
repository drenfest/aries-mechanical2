<script>
    import Hero from '../../components/Hero.svelte';
    import CouponSidebar from '../../components/CouponSidebar.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/hvacthero1.jpg"
        heroTitle="Residential Hvac Company"
        heroBigText="Affordable & Quality HVAC Services"
        heroText=" Your Hvac | A/C | Furnace Installation & Repair Company">
    <p>When winter arrives, or summer turns up the heat, call Aries Mechanical Inc. for climate control. Whether it is a repair, Maintenance or Installation.</p>
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
