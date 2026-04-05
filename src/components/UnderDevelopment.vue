<template>
    <main class="page">
        <section class="container">

            <!-- Header -->
            <header class="header">
                <h1 class="brand">Konnetto</h1>
                <p class="tagline">Let's build your otaku dream. Together.</p>
            </header>

            <!-- Illustration -->
            <section class="visual">
                <img src="/development.jpg"
                    alt="A calm anime-style illustration of a developer coding comfortably at night" />
            </section>

            <!-- Content -->
            <section class="content">
                <h2 class="title">We're still building.</h2>
                <p class="subtitle">Slowly, carefully, and on purpose.</p>

                <p>
                    Transforming the otaku world into a space where every dream can be built,
                    every contribution matters, and everyone proudly belongs.
                </p>

                <p>
                    We're not rushing this. The things that matter —
                    the warmth, the trust, the feeling that this place was made for you —
                    those take time to get right.
                </p>

                <p class="closing">
                    Thanks for being here early.
                </p>

                <p class="final">
                    <strong>When it's ready, you'll feel it.</strong>
                </p>

                <p class="see-you">See you soon.</p>
            </section>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <p>Because in this world — every otaku deserves to see their dream become real.</p>
            <span>© 2026 PT Wibu Kreatif Berkarya</span>
        </footer>
    </main>
</template>

<script setup lang="ts">
// Intentionally no logic.
// This page is designed to feel calm, stable, and complete.
</script>

<style scoped>
/* ===== Theme ===== */
:root {
    --purple-main: #4f46e5;
    --purple-soft: #eef2ff;
    --text-main: #1f2937;
    --text-muted: #6b7280;
    --bg-main: #ffffff;
}

/* ===== Layout ===== */
.page {
    min-height: 100vh;
    background: linear-gradient(180deg,
            var(--purple-soft) 0%,
            var(--bg-main) 65%);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 48px 16px 32px;
    color: var(--text-main);
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, Helvetica, Arial, sans-serif;
}

.container {
    max-width: 720px;
    margin: 0 auto;
    text-align: center;
}

/* ===== Header ===== */
.header {
    margin-bottom: 40px;
}

.brand {
    font-size: 36px;
    font-weight: 700;
    letter-spacing: -0.02em;
    color: var(--purple-main);
    margin-bottom: 8px;
}

.tagline {
    font-size: 14px;
    color: var(--text-muted);
    font-style: italic;
}

/* ===== Visual ===== */
.visual {
    margin: 0 auto 40px;
}

.visual img {
    width: 100%;
    max-width: 360px;
    border-radius: 18px;
}

/* ===== Content ===== */
.content {
    font-size: 15px;
    line-height: 1.8;
}

.title {
    font-size: 24px;
    font-weight: 600;
    margin-bottom: 6px;
}

.subtitle {
    font-size: 15px;
    color: var(--text-muted);
    margin-bottom: 20px;
}

.content p {
    margin: 14px 0;
}

.closing {
    margin-top: 28px;
    color: var(--text-muted);
}

.final {
    margin-top: 12px;
}

.see-you {
    margin-top: 24px;
    font-weight: 500;
    color: var(--text-muted);
}

/* ===== Footer ===== */
.footer {
    text-align: center;
    font-size: 13px;
    color: var(--text-muted);
    margin-top: 40px;
}

.footer p {
    font-style: italic;
}

.footer span {
    display: block;
    margin-top: 6px;
    font-size: 12px;
}
</style>
