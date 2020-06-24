<script>
export let title;
export let date;

let niceDate = new Date(date).toLocaleDateString();
</script>

<h1>{ title }</h1>
<h2>Posted on { niceDate }</h2>

<slot></slot>