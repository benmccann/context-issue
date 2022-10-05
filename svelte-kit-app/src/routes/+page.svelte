<script>
	import { testSetContext } from 'tmp-context-issue';

	// It works with a local dependency
	// import { testSetContext } from '../../../package/dist/index';

	testSetContext();
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
