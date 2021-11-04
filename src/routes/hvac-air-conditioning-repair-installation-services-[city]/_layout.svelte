<script context="module">
    export async function preload({params, query}){
        // return this.fetch(`/nn-filler.html/`)
        // 		.then((r) => {
        // 			r.text().then((nnText) =>{
        // 				return content = nnText;
        // 			});
        // 		})
        let cs = await params.city.split("-");
        let state = await cs[cs.length - 1].toUpperCase();
        let city = await params.city.replace("-"+state.toLowerCase(),'').replace('-',' ').replace(params.city.substr(0,1),params.city.substr(0,1).toUpperCase());
        return {nnCity:city,nnState:state};
    }
</script>
<script>
    import Hero from '../../components/Hero.svelte';
    import CouponSidebar from '../../components/CouponSidebar.svelte';
    let locations;
    export let nnCity;
    let nnState="IL";
</script>
<style>

</style>
<Hero heroImage="/assets/images/heros/achero1.jpg" heroTitle="Aries Mechanical" heroBigText="Air Conditioning Repair, Service & Installation in {nnCity}, {nnState}" heroText=" {nnCity}, {nnState} A/C Repair Company">
    <p>It may be time to call Aries Mechanical Inc., your {nnCity}, {nnState} HVAC experts. Our trained and certified hvac specialists have the expertise and knowledge to guide you into total home cooling.</p>
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
