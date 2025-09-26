<script>
    import Header from "../components/Header.svelte";
</script>

<div class="min-h-screen flex flex-col">
    <Header />

    <main
        class="flex flex-1 flex-col items-center justify-center text-center px-4 py-20"
    >
        <h1 class="text-5xl font-bold mb-4">Catch issues in seconds</h1>
        <h1 class="text-5xl font-bold">Scale without limits</h1>
        <h4 class="text-lg text-gray-500 max-w-2xl my-8">
            The log monitoring platform for your servers. Start monitoring
            instantly by deploying a lightweight agent, with real-time alerts,
            instant dashboards, live analytics, and secure log storage.
        </h4>
        <div class="flex gap-4">
            <button
                class="text-sm bg-indigo-500 text-white font-semibold px-6 py-2 rounded-lg border-1 border-indigo-600 hover:border-indigo-100"
            >
                Get started
            </button>
        </div>
    </main>
</div>
