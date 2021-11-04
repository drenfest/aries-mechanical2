<script>
export let segment ="";
</script>
<style>
    .sidebar-subnav {
        padding: 2rem 1rem;
    }

    .sidebar-subnav ul {
       margin: 0;
    padding: 0;
    list-style-type: none;
    font-family: 'Oswald', sans-serif;
    font-size: 14px;
    /* border: 2px solid var(--success); */
    background-color: #efefef;
    padding: 15px 0px;
    background-image:url("/assets/images/subnavbk.png");
    background-position:bottom right;
   background-repeat: no-repeat;


    }

    .sidebar-subnavli {
        margin: 0 0 3px 0;
    }

    .sidebar-subnav a {
    display: block;
    padding: .25rem 0rem;
    font-weight: 400;
    color: var(--success);
    font-size: 22px;
    font-family: 'Oswald', sans-serif;
    text-transform: uppercase;
    padding: .5rem 2rem;
    }

    .sidebar-subnav a:hover {
        background-color:transparent;
        color: var(--primary-color);
        text-decoration: none;
    }

</style>
<section class="sidebar-subnav">
    <ul>
        <li>
            <a class="heating" rel=prefetch href='heating' title="Heating">Heating</a>
        </li>
        <li>
            <a class="cooling" rel=prefetch href='cooling' title="Cooling">Cooling</a>
        </li>
        <li>
            <a class="humidification" rel=prefetch href='humidification' title="Humidification">Humidification</a>
        </li>
        <li>
            <a class="reviews" rel=prefetch href='reviews' title="Reviews">Reviews</a>
        </li>
        <li>
            <a class="special" rel=prefetch href='special' title="Specials">Specials</a>
        </li>
        <li>
            <a class="contact" rel=prefetch href='contact' title="Contact Us">Contact</a>
        </li>
    </ul>
</section>
