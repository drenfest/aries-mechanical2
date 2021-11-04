<script>
    import Hero from '../../components/Hero.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/specialhero1.jpg"
        heroTitle="Aries Mechanical"
        heroBigText="Current Specials"
        heroText="HVAC Services For Over 30 Years">
    <p>10-Year Limited Warranty on parts.  Experience significant cost-savings today with our special coupons and sales; call us at 815-695-5828.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
        <section class="content">
            <slot></slot>
        </section>
</div>
