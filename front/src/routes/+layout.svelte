<script lang="ts">
	import '$lib/app.css';
	const { children } = $props();
</script>

<header>
	<a href="/">slog</a>
	<a href="/member/login">로그인</a>
	<a href="/member/join">회원가입</a>
</header>
<main>{@render children()}</main>
<footer>푸터</footer>
