<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Intermediario Financiero | Tu Préstamo Ideal</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-blue-600">FinanExpert</div>
            <a href="#contacto" class="bg-blue-600 text-white px-5 py-2 rounded-lg font-semibold hover:bg-blue-700 transition">Solicitar Ahora</a>
        </div>
    </nav>

    <section class="py-16 px-4 text-center bg-gradient-to-b from-blue-50 to-white">
        <h1 class="text-4xl md:text-5xl font-bold mb-6 text-gray-900">El préstamo que necesitas, <br><span class="text-blue-600">con las mejores condiciones.</span></h1>
        <p class="text-lg text-gray-600 mb-8 max-w-2xl mx-auto">Conectamos tu perfil con los principales bancos para conseguirte la tasa más baja. Sin papeleo excesivo y con respuesta rápida.</p>
        <div class="flex flex-col md:flex-row justify-center gap-4">
            <a href="#contacto" class="bg-blue-600 text-white px-8 py-4 rounded-xl text-lg font-bold shadow-lg hover:bg-blue-700 transition">Quiero mi estudio gratuito</a>
        </div>
    </section>

    <section class="py-16 max-w-6xl mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">¿Cómo funciona?</h2>
        <div class="grid md:grid-cols-3 gap-8">
            <div class="text-center p-6 bg-white rounded-2xl shadow-sm border border-gray-100">
                <div class="bg-blue-100 w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 text-blue-600 font-bold text-xl">1</div>
                <h3 class="font-semibold text-xl mb-2">Completa el formulario</h3>
                <p class="text-gray-500 text-sm">Solo te tomará 2 minutos. Sin compromisos.</p>
            </div>
            <div class="text-center p-6 bg-white rounded-2xl shadow-sm border border-gray-100">
                <div class="bg-blue-100 w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 text-blue-600 font-bold text-xl">2</div>
                <h3 class="font-semibold text-xl mb-2">Analizamos tu perfil</h3>
                <p class="text-gray-500 text-sm">Buscamos la mejor opción entre múltiples entidades financieras.</p>
            </div>
            <div class="text-center p-6 bg-white rounded-2xl shadow-sm border border-gray-100">
                <div class="bg-blue-100 w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 text-blue-600 font-bold text-xl">3</div>
                <h3 class="font-semibold text-xl mb-2">Recibe tu dinero</h3>
                <p class="text-gray-500 text-sm">Te acompañamos en todo el proceso hasta que tengas el capital.</p>
            </div>
        </div>
    </section>

    <section id="contacto" class="py-16 bg-blue-600">
        <div class="max-w-xl mx-auto px-4">
            <div class="bg-white p-8 rounded-3xl shadow-2xl">
                <h2 class="text-2xl font-bold mb-6 text-center text-gray-800">Solicita información hoy</h2>
                <form action="#" method="POST" class="space-y-4">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-1">Nombre Completo</label>
                        <input type="text" placeholder="Ej. Juan Pérez" class="w-full border-gray-300 rounded-lg p-3 border focus:ring-2 focus:ring-blue-500 outline-none" required>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-1">Monto deseado ($)</label>
                        <input type="number" placeholder="Ej. 10000" class="w-full border-gray-300 rounded-lg p-3 border focus:ring-2 focus:ring-blue-500 outline-none" required>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-1">Teléfono de contacto</label>
                        <input type="tel" placeholder="Ej. +507 0000 0000" class="w-full border-gray-300 rounded-lg p-3 border focus:ring-2 focus:ring-blue-500 outline-none" required>
                    </div>
                    <button type="submit" class="w-full bg-orange-500 hover:bg-orange-600 text-white font-bold py-4 rounded-xl shadow-lg transition duration-300 uppercase tracking-wide">
                        Enviar solicitud
                    </button>
                    <p class="text-center text-xs text-gray-400 mt-4 italic text-balance">
                        🛡️ Tus datos están protegidos y solo se usarán para esta asesoría.
                    </p>
                </form>
            </div>
        </div>
    </section>

    <footer class="py-8 bg-gray-900 text-white text-center">
        <p class="text-sm text-gray-500">© 2026 FinanExpert - Intermediación Bancaria. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
