<template>
    <main class="page">
        <section class="container">
            <!-- Header -->
            <header class="header">
                <h1 class="brand">Konnetto</h1>
                <p class="tagline">Where Otaku Communities Live</p>
            </header>

            <!-- Illustration -->
            <section class="visual">
                <!-- 
          Replace this image with your final illustration asset.
          Example: /assets/konnetto-under-development.png
        -->
                <img src="/development.jpg"
                    alt="A calm anime-style illustration of a developer coding comfortably at night" />
            </section>

            <!-- Content -->
            <section class="content">
                <h2 class="title">We’re still building Konnetto.</h2>
                <p class="subtitle">And yeah — we’re doing it slowly, on purpose.</p>

                <p>
                    We want Konnetto to feel like a place you actually want to stay in.
                    Not rushed. Not loud. Not just another feature list.
                </p>

                <p>
                    A space where creators and fans can connect in a way that feels human,
                    and where fans can find each other without awkwardness or pressure.
                </p>

                <blockquote>
                    “Is it a bug, or is it just personality?”
                    <span>— our lead dev, probably</span>
                </blockquote>

                <p>
                    Right now, we’re deep in the <em>polishing-the-details</em> phase.
                    The small things. The flow. The tone.
                    The parts you only notice when they’re done right.
                </p>

                <p>
                    We believe emotional warmth and community trust can’t be shipped on a
                    deadline.
                </p>

                <p class="closing">
                    Thanks for being here early.
                    <br />
                    No hype. No countdown. Just intention.
                </p>

                <p class="final">
                    We’re building something we genuinely want to use ourselves.
                    <br />
                    <strong>When it’s ready, you’ll feel it.</strong>
                </p>

                <p class="see-you">See you soon.</p>
            </section>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <p>Thanks for waiting with us.</p>
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
    --green-main: #06c755;
    --green-soft: #eaf9f0;
    --text-main: #1f2937;
    --text-muted: #6b7280;
    --bg-main: #ffffff;
}

/* ===== Layout ===== */
.page {
    min-height: 100vh;
    background: linear-gradient(180deg,
            var(--green-soft) 0%,
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
    font-size: 34px;
    font-weight: 700;
    letter-spacing: -0.02em;
    color: var(--green-main);
    margin-bottom: 6px;
}

.tagline {
    font-size: 14px;
    color: var(--text-muted);
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

blockquote {
    margin: 28px auto;
    padding: 16px 20px;
    border-left: 4px solid var(--green-main);
    background: #f9fafb;
    border-radius: 10px;
    font-size: 14px;
    color: #374151;
}

blockquote span {
    display: block;
    margin-top: 6px;
    font-size: 13px;
    color: var(--text-muted);
}

.closing {
    margin-top: 24px;
    color: var(--text-muted);
}

.final {
    margin-top: 16px;
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

.footer span {
    display: block;
    margin-top: 6px;
    font-size: 12px;
}
</style>
