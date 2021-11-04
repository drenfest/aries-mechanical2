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
	<title>Air Conditioning Repair, Service & Installation in {nnCity}, {nnState}</title>
	<meta name="description" content="It may be time to call Aries Mechanical Inc., your {nnCity}, {nnState} HVAC experts. Our trained and certified hvac specialists have the expertise and knowledge to guide you into total home cooling.">
</svelte:head>


<h2>Aries Mechanical - Air Conditioning Repair, Service and Installation in {nnCity}, {nnState}</h2>
<h3>Air Conditioning {nnCity}, {nnState}</h3>
<p>Humidity and the summer heat can interrupt a good night&rsquo;s rest&nbsp;and make your home unbearable. It may be time to call Aries Mechanical Inc., your local neighborhood HVAC experts. Our trained and certified specialists have the expertise and knowledge to keep your home comfortable. Whether you&rsquo;re in the market for new installation, repairs, or maintenance Aries Mechanical Inc. does it all. Available 24/7 we will work within your schedule, budget and specifications to keep&nbsp;you out of the Chicago heat.</p>
<p>If you&rsquo;ve ever considered installing Central Air Conditioning, A/C or HVAC system, then there&rsquo;s never a better time than now. Low prices, Energy Star rebates and high efficiency air conditioners are more affordable than ever. Improvements on compressor technology and fan blade shapes on most units make less than 1/10 the noise of old units. The average HVAC unit 20 years ago utilized 6,000 watts of electricity per hour to cool the average home. Today, that same home can be kept cool with as little as 1,800 watts per hour. Technology has introduced many innovative features, such as programmable thermostats, allowing you to control your homes temperature even while you&rsquo;re on vacation.</p>
<h3>New A/C Installation {nnCity}, {nnState}</h3>
<p>Aries Mechanical Inc. has partnered with Trane&reg;, providing our customers with the most reliable and some of the quietest systems available. Armstrong central air conditioners offer SEER ratings of up to 18, and continue to rank among the worlds best. As a certified Trane&reg; HVAC dealer, our technicians are fully trained in installation. We respect your home and strive to complete all jobs with as little intrusion as possible.</p>
<h3>A/C Repair {nnCity}, {nnState}</h3>
<p>Aries Mechanical Inc. certified technicians are here to serve all your homes comfort needs. We service and repair all makes and models. When you call on us, count on prompt reliable action. We understand breakdowns tend to happened at the worst possible times. We won&rsquo;t leave you melting until Monday sweating in the summer heat. Call 815-695-5828</p>
<h3>A/C Service {nnCity}, {nnState}</h3>
<p>A great way to avoid inconvenient repairs is through a preventative maintenance program. Aries Mechanical Inc. will gladly tailor a maintenance program to meet your specifications. Our certified technicians will analyze your air conditioning system, and pinpoint worn or broken parts. Scheduling a regular visit will maximize your systems performance and increase efficiency, eliminating most repair needs and lengthen the lifespan of your unit lowering utility bills.</p>
<h3>Contact us Today!</h3>
<p>If you&rsquo;re looking to install, repair or service a central air conditioner Aries Mechanical Inc. is the right choice. Customer satisfaction is a top priority and work to build relationships in the {nnCity}, {nnState} area by exceeding expectations. Give us a call today.</p>
<h3>Call 815-695-5828 to speak with a member of our professional service team!</h3>
