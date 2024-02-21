<script>
  import { Router, Route } from 'svelte-routing';
  import DocsPage from './components/docs/docsPage.svelte';
  import DocPage from './components/docs/docPage.svelte';
  import NotFoundPage from './components/notFoundPage.svelte';
</script>

<div>
  <Router>
    <Route path="/" component={DocsPage} />
    <Route path="" component={NotFoundPage} />
    <Route path="/docs/:docId" component={DocPage} />
  </Router>
</div>