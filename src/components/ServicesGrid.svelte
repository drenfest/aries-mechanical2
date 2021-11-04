<script>

</script>
<style>
    .grid{
        display:grid;
        grid-template-columns: 1fr;
        grid-gap:1rem;
        text-align:center;
        padding:3rem 1rem;
    }
    .service{
        display:flex;
        flex-direction:column;
        justify-content:center;
        min-height:300px;
        max-height:300px;
        font-size:2rem;
        color:white;
        font-weight:bold;
        background-color:rgba(0,0,0,.4);
        background-blend-mode:overlay;
        font-family: 'Oswald', sans-serif;
        background-size: cover;
        background-position: center center;

    }
    .service-heating{
        background-image:url("/assets/images/services/service1.jpg");
    }
    .service-ac{
        background-image:url("/assets/images/services/service2.jpg");
    }
    .service-air-cleaning{
        background-image:url("/assets/images/services/service3.jpg");
    }
    .service-res-hvac{
        background-image:url("/assets/images/services/service4.jpg");
    }
    .service-humidify{
        background-image:url("/assets/images/services/service-humidification.jpg");
    }
    .service-thermostats{
        background-image:url("/assets/images/services/service5.jpg");
    }
    @media screen and (min-width:768px){
        .grid{
            grid-template-columns: 1fr 1fr;
        }
    }
    @media screen and (min-width:992px){
        .grid{
            grid-template-columns: 1fr 1fr 1fr;
        }
    }
</style>
<section class="services-grid">
    <div class="container">
        <div class="grid">
            <a class="service service-heating" title="Read About Our Heating Services" href="/heating">Heating</a>
            <a class="service service-ac" title="Read About Our Air Conditioning" href="/conditioning">Air Conditioning</a>
            <a class="service service-air-cleaning" title="Read About Our Air Cleaning And Purifying Services" href="/air-cleaning">Air Cleaning</a>
            <a class="service service-res-hvac" title="Read About Our Residential Services" href="/residential-hvac">Residential Hvac</a>
            <a class="service service-thermostats" title="Read About Programmable Thermostats" href="/programmable">Thermostats</a>
            <a class="service service-humidify" title="Read About Our Furnace Repair Services" href="/furnace-repair">Furnace Repair</a>
        </div>
    </div>
</section>
