<script>
    import Hero from '../../components/Hero.svelte';
    import CouponSidebar from '../../components/CouponSidebar.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/progthermohero1.jpg"
        heroTitle="Programmable Thermostats"
        heroBigText="Affordable & Quality HVAC Services For Over 30 Years"
        heroText=" Your Hvac | A/C | Programmable Thermostat Installation & Repair Company">
    <p>Families have ever-changing schedules and access to Smart Thermostats from anywhere to control their home.</p>
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
