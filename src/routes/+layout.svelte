<script>	
	import '../app.css';
	import '../styles.css';
	let src = '../src/lib/images/image-qr-code.png'

</script>


<body class="bg-indigo-200 flex items-center justify-center m-10">

    <div class="container bg-slate-50 flex-col w-80 p-4 rounded-xl shadow-2xl">
		<!--imagen codigo central-->
        <div class="flex items-center justify-center">
            <!-- svelte-ignore a11y-missing-attribute -->
            <img {src} class="rounded-xl" />              
        </div>  
		<!--subtitulo y texto-->
        <div class="text-center py-6">
            <h1 class="font-bold">Improve your front-end skills by building projects</h1>
            <p class="text-gray-400">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>                
        </div>
    </div>
</body>

