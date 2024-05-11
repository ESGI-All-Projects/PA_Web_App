<script>
	// Importez tous les composants ici
	import Header from './components/Header.svelte';
	import BalanceSummary from './components/BalanceSummary.svelte';
	import LineChart from './components/LineChart.svelte';
	import ActionButtons from './components/ActionButtons.svelte';
	import CryptoList from './components/CryptoList.svelte';

	import "./homepage.css";
</script>
<div class="gradient-custom">
	<Header />
	<BalanceSummary />
	<LineChart />
	<ActionButtons />
	<CryptoList />
</div>




