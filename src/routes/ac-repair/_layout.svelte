<script>
         import Hero from '../../components/Hero.svelte';
      import ProductGuide from '../../components/ProductGuide.svelte';
     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/achero1.jpg"
        heroTitle="Aries Mechanical"
        heroBigText="Air Conditioner Repair"
        heroText=" Your A/C Repair Company">
    <p>We offer fast, affordable air conditioning repairs around the clock, and we dispatch all over the Chicago land area.</p>
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
