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
    export let nnCity;
    export let nnState="IL";
    export let locations = [
        {city:"Bristol", state:"IL"},
        {city:"Lisbon", state:"IL"},
        {city:"Millbrook", state:"IL"},
        {city:"Newark", state:"IL"},
        {city:"Norway", state:"IL"},
        {city:"Oswego", state:"IL"},
        {city:"Ottawa", state:"IL"},
        {city:"Plano", state:"IL"},
        {city:"Sandwich", state:"IL"},
        {city:"Sheridan", state:"IL"},
        {city:"Somonauk", state:"IL"},
        {city:"Sugar grove", state:"IL"},
        {city:"Yorkville", state:"IL"},
    ];
</script>
<style>
</style>
<svelte:head>
	<title>HVAC & Furnace Repair Services of {nnCity}, {nnState}</title>
	<meta name="description" content="For over 25 years, residents in {nnCity}, {nnState} have relied on Aries Mechanical to keep their families safe and their furnace systems running efficiently.">
</svelte:head>
<h2>Aries Mechanical for HVAC &amp; Furnace Repair Services of {nnCity}, {nnState}</h2>
<p>For over 25 years, residents in Chicago&rsquo;s western suburbs and {nnCity}, {nnState} have relied on Aries Mechanical to keep their families safe and their home systems running efficiently. We love what we do and it shows in our high-degree of personal and professional levels of service. We make your life easier and safer by providing top-notch heating, cooling, humidification and air cleaning services.</p>
<h3>HVAC Repair {nnCity}, {nnState}</h3>
<p>Whether it&rsquo;s a furnace or AC system that needs repair Aries Mechanical is the company to call. With over 25 years of experience our courteous technicians will determine the cause of system failure. We provide our customers with upfront pricing for repairs needed and perform a free safety check of the system. We discuss with our customers why the part failed and provide solutions to help prevent future breakdowns.</p>
<p>Aries Mechanical has extensive experience in installing and repairing high efficiency systems and the newest technologies in:</p>
<ul>
	<li>Air Cleaning</li>
	<li>Air Conditioners</li>
	<li>Dehumidification</li>
	<li>Humidification</li>
	<li>Duct Sealing</li>
	<li>Ducts &amp; Vents</li>
	<li>Gas Furnaces</li>
	<li>Programmable Thermostats</li>
</ul>
<ul>
	<li>Water Heaters</li>
	<li>Wireless Thermostats</li>
	<li>Energy Savings</li>
	<li>High Efficiency Furnaces</li>
	<li>High Efficiency AC</li>
	<li>Duct Sealing</li>
	<li>Indoor Air Quality</li>
</ul>
<h3>HVAC Installation {nnCity}, {nnState}</h3>
<p>Aries Mechanical takes pride in the quality of each and every installation that we do. After each installation we educate our customers with their new furnace or AC system and make sure they are completely satisfied with their installation.</p>
<h3>HVAC Cleaning &amp; Maintenance</h3>
<p>Aries Mechanical can clean and&nbsp;maintain all of your heating and cooling equipment. We perform a 14 step safety inspection &amp; cleaning on AC systems and a 12 step safety inspection &amp; cleaning on furnaces. Having your&nbsp;systems cleaned &amp; inspected on an annual basis will keep your energy cost to a minimum while keeping you comfortable and safe. We offer Preventive Maintenance Agreements.</p>
<h3>Expert Technicians</h3>
<p>The team at Aries Mechanical each have over 25 years of experience in the residential heating and cooling industry. Our technicians can read blueprints and schematics and have experience in sheet metal installation.</p>
<h3>Furnace Repair Services {nnCity}, {nnState}</h3>
<p>Throughout the {nnCity}, {nnState} area cold weather can come upon us within 24 hours.. At Aries Mechanical, we know you can never plan enough for emergency situations.&nbsp; We understand and recognize the severity of not having heat when it&#39;s -16 degrees outside.&nbsp; We service and repair all makes and models at reasonable prices.</p>
<h3>Here are just a few reasons why customers choose Aries Mechanical for heating repairs:</h3>
<ul>
	<li><strong>Affordable Repairs:</strong> After diagnosing the furnace, your technician will verify the repairs and cost before he performs the work. There are never any surprises at the end of the service!</li>
	<li><strong>All Makes and Models: </strong> Aries Mechanical can repair any furnace regardless of make and model!</li>
	<li><strong>Superior Service:</strong> Take a look at what our customers think under our reviews.</li>
	<li><strong>We Service Your Area: </strong> Aries Mechanical has a furnace repair technician close to your area.</li>
	<li><strong>24 Hour Service:</strong> 24 hours a day, 7 days a week, and 365 days a year.</li>
	<li><strong>Our work is Guaranteed: When you call Aries Mechanical all our work is guaranteed.</strong> We have some of the best warranties in the HVAC industry.</li>
</ul>
