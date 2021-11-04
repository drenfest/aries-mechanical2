<script>
    import Hero from '../../components/Hero.svelte';
  import ProductGuide from '../../components/ProductGuide.svelte';
     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
     </script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/humhero1.jpg"
        heroTitle="Affordable & Reliable"
        heroBigText="Humidification Solutions"
        heroText=" Your Humidifier Installation & Repair Company">
    <p>The Aries Mechanical team understands the decision to purchase a whole house humidifier takes careful consideration.</p>
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
