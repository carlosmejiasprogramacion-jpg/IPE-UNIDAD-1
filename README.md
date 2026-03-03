<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapa Mental - Unidad 1: La Prevención de Riesgos Laborales y la Salud Laboral</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @keyframes pulse-soft { 0%, 100% { opacity: 1; } 50% { opacity: 0.7; } }
        .animate-pulse-soft { animation: pulse-soft 2s ease-in-out infinite; }
        .concept-card { transition: all 0.3s ease; cursor: pointer; }
        .concept-card:hover { transform: translateY(-5px); box-shadow: 0 10px 25px rgba(0,0,0,0.2); }
        .info-box { background: #1e293b; color: #e2e8f0; padding: 1rem; border-radius: 0.5rem; font-size: 0.875rem; overflow-x: auto; }
    </style>
</head>
<body class="bg-gradient-to-br from-teal-50 via-cyan-50 to-emerald-50 min-h-screen p-6">
    <div class="max-w-7xl mx-auto">

        <div class="text-center mb-12">
            <h1 class="text-5xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-teal-600 to-cyan-600 mb-4 animate-pulse-soft">🛡️ UNIDAD 1: Prevención de Riesgos Laborales y Salud Laboral</h1>
            <p class="text-xl text-gray-700">Conoce tus derechos, identifica los riesgos y protege tu salud en el trabajo</p>
            <p class="text-sm text-gray-500 mt-2">📚 IPE I — DAM · Universidad Europea de Madrid</p>
        </div>

        <div class="mb-12 flex justify-center">
            <div class="bg-gradient-to-r from-teal-500 to-cyan-500 text-white p-8 rounded-3xl shadow-2xl max-w-3xl">
                <h2 class="text-3xl font-bold mb-4 text-center">🎯 ¿Qué vamos a aprender?</h2>
                <p class="text-lg text-center mb-4">En esta unidad aprenderás la relación entre <strong>TRABAJO y SALUD</strong>, el marco normativo de la prevención, los daños derivados del trabajo (accidentes y enfermedades profesionales), las técnicas de prevención y protección, y la señalización de seguridad.</p>
                <div class="bg-white/20 p-4 rounded-xl mt-4">
                    <p class="text-center text-lg font-semibold">🔑 Los 5 pilares de esta unidad:</p>
                    <p class="text-center mt-2 text-sm">1️⃣ Trabajo ↔ Salud → 2️⃣ Marco normativo (LPRL) → 3️⃣ Daños laborales → 4️⃣ Prevención y Protección → 5️⃣ Señalización</p>
                </div>
            </div>
        </div>

        <!-- ===== SECCIÓN 1: EL TRABAJO Y LA SALUD ===== -->
        <div class="mb-8"><h2 class="text-2xl font-bold text-teal-700 mb-6 border-b-2 border-teal-200 pb-2">💚 Sección 1: El Trabajo y la Salud</h2></div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-12">

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-teal-500" onclick="toggleDetail('b1')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🏥</span><h3 class="text-2xl font-bold text-teal-600">1. Concepto de Salud</h3></div>
                <p class="text-gray-600 mb-4">No es solo ausencia de enfermedad</p>
                <div id="b1" class="hidden mt-4 text-sm text-gray-700">
                    <div class="info-box mb-3">Salud = Estado de completo bienestar FÍSICO, MENTAL y SOCIAL (OMS + OIT)</div>
                    <ul class="list-disc list-inside space-y-2">
                        <li><strong>Físico:</strong> Funcionamiento correcto de células, tejidos y órganos</li>
                        <li><strong>Psíquico:</strong> Equilibrio intelectual y emocional</li>
                        <li><strong>Social:</strong> Bienestar en las relaciones sociales</li>
                    </ul>
                    <p class="mt-3 text-xs text-teal-700">💡 Recuerda: Salud = Bienestar en las 3 dimensiones, NO solo "no estar enfermo"</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-green-500" onclick="toggleDetail('b2')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🔄</span><h3 class="text-2xl font-bold text-green-600">2. Relación Trabajo ↔ Salud</h3></div>
                <p class="text-gray-600 mb-4">El trabajo afecta positiva y negativamente</p>
                <div id="b2" class="hidden mt-4 text-sm text-gray-700">
                    <p class="mb-2 font-semibold text-green-600">✅ Efectos POSITIVOS:</p>
                    <ul class="list-disc list-inside space-y-1 mb-3">
                        <li>Proporciona recursos económicos</li>
                        <li>Favorece el desarrollo personal y profesional</li>
                    </ul>
                    <p class="mb-2 font-semibold text-red-600">❌ Efectos NEGATIVOS:</p>
                    <ul class="list-disc list-inside space-y-1">
                        <li>Conlleva riesgos laborales</li>
                        <li>Puede generar daños en la salud</li>
                    </ul>
                    <p class="mt-3 text-xs text-green-700">🔑 Clave examen: El trabajo y la salud están INTERRELACIONADOS → por eso existe la prevención</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-blue-500" onclick="toggleDetail('b3')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">⚖️</span><h3 class="text-2xl font-bold text-blue-600">3. Derecho a la Seguridad</h3></div>
                <p class="text-gray-600 mb-4">Reconocido en normas nacionales e internacionales</p>
                <div id="b3" class="hidden mt-4 text-sm text-gray-700">
                    <p class="mb-2 font-semibold">🌍 Normas internacionales:</p>
                    <ul class="list-disc list-inside space-y-1 mb-3">
                        <li><strong>UE:</strong> Directiva Marco 89/391 → deber de empresas de garantizar seguridad</li>
                        <li><strong>OIT:</strong> Derecho a entorno de trabajo seguro y saludable</li>
                    </ul>
                    <p class="mb-2 font-semibold">🇪🇸 Normas nacionales:</p>
                    <ul class="list-disc list-inside space-y-1">
                        <li><strong>Constitución (art. 40.2):</strong> Poderes públicos deben velar por la seguridad</li>
                        <li><strong>LPRL:</strong> Protección eficaz en seguridad y salud</li>
                        <li><strong>Estatuto de los Trabajadores:</strong> Derecho a integridad física</li>
                    </ul>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-yellow-500" onclick="toggleDetail('b4')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">📋</span><h3 class="text-2xl font-bold text-yellow-600">4. Conceptos Clave PRL</h3></div>
                <p class="text-gray-600 mb-4">Prevención, riesgo laboral y daño</p>
                <div id="b4" class="hidden mt-4 text-sm text-gray-700">
                    <div class="bg-teal-50 p-3 rounded mb-2">
                        <p><strong>🛡️ Prevención:</strong> Conjunto de medidas adoptadas en TODAS las fases de la actividad para <strong>evitar o disminuir</strong> los riesgos del trabajo.</p>
                    </div>
                    <div class="bg-yellow-50 p-3 rounded mb-2">
                        <p><strong>⚠️ Riesgo laboral:</strong> <strong>Posibilidad</strong> de que un trabajador sufra un daño derivado del trabajo. Gravedad = probabilidad × consecuencias.</p>
                    </div>
                    <div class="bg-red-50 p-3 rounded mb-2">
                        <p><strong>💥 Daño derivado:</strong> Enfermedades, patologías o lesiones sufridas con motivo u ocasión del trabajo.</p>
                    </div>
                    <div class="info-box mt-3">Factor de riesgo (CAUSA) → Riesgo laboral (POSIBILIDAD) → Daño (CONSECUENCIA)</div>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-red-500" onclick="toggleDetail('b5')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">⚙️</span><h3 class="text-2xl font-bold text-red-600">5. Condiciones de Trabajo</h3></div>
                <p class="text-gray-600 mb-4">Características que generan riesgos</p>
                <div id="b5" class="hidden mt-4 text-sm text-gray-700">
                    <div class="info-box mb-3">Condición de trabajo = cualquier característica que pueda influir en la generación de riesgos (LPRL)</div>
                    <table class="w-full text-xs border-collapse">
                        <tr class="bg-red-50"><th class="border p-2">Elemento</th><th class="border p-2">Ejemplos</th></tr>
                        <tr><td class="border p-2">Locales, instalaciones y equipos</td><td class="border p-2">Escaleras, máquinas, instalaciones eléctricas</td></tr>
                        <tr><td class="border p-2">Agentes químicos, físicos, biológicos</td><td class="border p-2">Ruido, vibraciones, virus, polvo</td></tr>
                        <tr><td class="border p-2">Procedimientos de utilización</td><td class="border p-2">Manipulación de contaminantes</td></tr>
                        <tr><td class="border p-2">Organización del trabajo</td><td class="border p-2">Ritmo elevado, turnos, nocturnidad</td></tr>
                    </table>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-purple-500" onclick="toggleDetail('b6')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🎯</span><h3 class="text-2xl font-bold text-purple-600">6. Factores de Riesgo</h3></div>
                <p class="text-gray-600 mb-4">4 grandes grupos según su origen</p>
                <div id="b6" class="hidden mt-4 text-sm text-gray-700">
                    <table class="w-full text-xs border-collapse">
                        <tr class="bg-purple-50"><th class="border p-2">Factor</th><th class="border p-2">Origen</th><th class="border p-2">Daños</th></tr>
                        <tr><td class="border p-2 font-bold">Condiciones de seguridad</td><td class="border p-2">Lugares, equipos, electricidad, incendios</td><td class="border p-2">Accidentes de trabajo</td></tr>
                        <tr><td class="border p-2 font-bold">Condiciones ambientales</td><td class="border p-2">Agentes físicos, químicos, biológicos</td><td class="border p-2">Enfermedades profesionales</td></tr>
                        <tr><td class="border p-2 font-bold">Carga de trabajo</td><td class="border p-2">Carga física (posturas) + mental (información)</td><td class="border p-2">Fatiga, trastornos musculoesqueléticos</td></tr>
                        <tr><td class="border p-2 font-bold">Organización del trabajo</td><td class="border p-2">Monotonía, estilo de mando, comunicación</td><td class="border p-2">Estrés, burnout, mobbing</td></tr>
                    </table>
                    <p class="mt-3 text-xs text-purple-700">⚠️ Típico de examen: Clasificar un riesgo en su grupo correcto</p>
                </div>
            </div>
        </div>

        <!-- ===== SECCIÓN 2: MARCO NORMATIVO ===== -->
        <div class="mb-8"><h2 class="text-2xl font-bold text-teal-700 mb-6 border-b-2 border-teal-200 pb-2">📜 Sección 2: El Marco Normativo de la PRL</h2></div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-12">

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-teal-500" onclick="toggleDetail('b7')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">📕</span><h3 class="text-2xl font-bold text-teal-600">7. Ley de PRL (LPRL)</h3></div>
                <p class="text-gray-600 mb-4">Ley 31/1995 — Norma básica en España</p>
                <div id="b7" class="hidden mt-4 text-sm text-gray-700">
                    <div class="info-box mb-3">Constitución (art. 40.2) + Directiva europea 89/391 + Convenio 155 OIT
    ↓
Ley 31/1995 de PRL (LPRL)
    ↓
Reglamentos de desarrollo</div>
                    <ul class="list-disc list-inside space-y-2 mt-3">
                        <li>Establece conceptos básicos de PRL</li>
                        <li>Determina obligaciones de las empresas</li>
                        <li>Reconoce derechos de los trabajadores</li>
                        <li>Es la <strong>BASE</strong> de toda la legislación en España sobre seguridad y salud laboral</li>
                    </ul>
                    <p class="mt-3 text-xs text-teal-700">📌 Se aplica tanto a relaciones del TRET como a Administraciones públicas</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-orange-500" onclick="toggleDetail('b8')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">👷</span><h3 class="text-2xl font-bold text-orange-600">8. Obligaciones del Trabajador</h3></div>
                <p class="text-gray-600 mb-4">La prevención es cosa de TODOS</p>
                <div id="b8" class="hidden mt-4 text-sm text-gray-700">
                    <ul class="list-disc list-inside space-y-2">
                        <li><strong>Velar</strong> por su propia seguridad y salud y la de los demás</li>
                        <li><strong>Usar adecuadamente</strong> máquinas, herramientas, sustancias peligrosas...</li>
                        <li><strong>Utilizar correctamente</strong> los dispositivos de seguridad y EPI</li>
                        <li><strong>Informar</strong> a superiores si detectan un riesgo</li>
                        <li><strong>Cooperar</strong> con la empresa para garantizar condiciones seguras</li>
                    </ul>
                    <p class="mt-3 text-xs text-orange-700">⚠️ Si incumplen → Responsabilidad DISCIPLINARIA (hasta despido)</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-blue-500" onclick="toggleDetail('b9')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🏢</span><h3 class="text-2xl font-bold text-blue-600">9. Obligaciones de la Empresa</h3></div>
                <p class="text-gray-600 mb-4">Debe garantizar protección eficaz</p>
                <div id="b9" class="hidden mt-4 text-sm text-gray-700">
                    <ul class="list-disc list-inside space-y-2">
                        <li><strong>Plan de prevención:</strong> Integrar la prevención en la gestión</li>
                        <li><strong>Evaluación de riesgos:</strong> De cada puesto y generales</li>
                        <li><strong>Planificación:</strong> Medidas para eliminar/reducir riesgos</li>
                        <li><strong>Información:</strong> Sobre condiciones y riesgos del puesto</li>
                        <li><strong>Formación:</strong> Teórica y práctica, obligatoria, gratuita, en horario laboral</li>
                        <li><strong>Vigilancia de la salud:</strong> Reconocimientos periódicos (voluntarios salvo excepciones)</li>
                        <li><strong>Protección especial:</strong> Menores, maternidad, trabajadores sensibles</li>
                        <li><strong>Emergencias:</strong> Primeros auxilios, incendios, evacuación</li>
                        <li><strong>EPI:</strong> Proporcionar equipos de protección individual gratuitos</li>
                    </ul>
                    <p class="mt-3 text-xs text-blue-700">🔑 La formación es OBLIGATORIA y GRATUITA. Si es fuera de horario → se compensa con descanso</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-red-500" onclick="toggleDetail('b10')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">⚖️</span><h3 class="text-2xl font-bold text-red-600">10. Responsabilidades PRL</h3></div>
                <p class="text-gray-600 mb-4">Consecuencias del incumplimiento</p>
                <div id="b10" class="hidden mt-4 text-sm text-gray-700">
                    <p class="mb-2 font-semibold">🏢 Responsabilidades de la EMPRESA:</p>
                    <table class="w-full text-xs border-collapse mb-3">
                        <tr class="bg-red-50"><th class="border p-2">Tipo</th><th class="border p-2">Sanciones</th></tr>
                        <tr><td class="border p-2 font-bold">Administrativa</td><td class="border p-2">Multas, suspensión, paralización, cierre</td></tr>
                        <tr><td class="border p-2 font-bold">Recargo prestaciones</td><td class="border p-2">+30% a +50% en prestaciones de SS (a cargo de la empresa)</td></tr>
                        <tr><td class="border p-2 font-bold">Civil</td><td class="border p-2">Indemnización por daños físicos o morales</td></tr>
                        <tr><td class="border p-2 font-bold">Penal</td><td class="border p-2">Prisión, multa, inhabilitación</td></tr>
                    </table>
                    <p class="mb-2 font-semibold">👷 Responsabilidad del TRABAJADOR:</p>
                    <div class="bg-orange-50 p-2 rounded">
                        <p><strong>Disciplinaria:</strong> Según la gravedad → amonestación hasta despido</p>
                    </div>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-green-500" onclick="toggleDetail('b10b')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🤰</span><h3 class="text-2xl font-bold text-green-600">11. Protecciones Especiales</h3></div>
                <p class="text-gray-600 mb-4">Menores, maternidad y sensibles</p>
                <div id="b10b" class="hidden mt-4 text-sm text-gray-700">
                    <p class="mb-2 font-semibold">👶 Protección de MENORES:</p>
                    <ul class="list-disc list-inside space-y-1 mb-3 text-xs">
                        <li>Evaluación de riesgos ANTES de incorporarse (por su inexperiencia)</li>
                        <li>Informar a menores Y a sus progenitores/tutores</li>
                        <li>Prohibido trabajos peligrosos, nocivos, insalubres</li>
                    </ul>
                    <p class="mb-2 font-semibold">🤰 Protección de la MATERNIDAD:</p>
                    <ul class="list-disc list-inside space-y-1 mb-3 text-xs">
                        <li>1º Adaptar condiciones/jornada</li>
                        <li>2º Asignar otro puesto sin riesgo</li>
                        <li>3º Suspender contrato por riesgo para el embarazo/lactancia</li>
                    </ul>
                    <p class="mb-2 font-semibold">🩺 Trabajadores ESPECIALMENTE SENSIBLES:</p>
                    <p class="text-xs">Garantizar seguridad de quienes por características personales o estado físico/psíquico sean más vulnerables</p>
                </div>
            </div>
        </div>

        <!-- ===== SECCIÓN 3: DAÑOS DERIVADOS DEL TRABAJO ===== -->
        <div class="mb-8"><h2 class="text-2xl font-bold text-teal-700 mb-6 border-b-2 border-teal-200 pb-2">💥 Sección 3: Los Daños Derivados del Trabajo</h2></div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-12">

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-red-500" onclick="toggleDetail('b11')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🚑</span><h3 class="text-2xl font-bold text-red-600">12. Accidente de Trabajo</h3></div>
                <p class="text-gray-600 mb-4">Lesión corporal, repentina e inesperada</p>
                <div id="b11" class="hidden mt-4 text-sm text-gray-700">
                    <div class="info-box mb-3">"Toda LESIÓN CORPORAL que el trabajador sufra con OCASIÓN o como CONSECUENCIA del trabajo por cuenta ajena" (LGSS)</div>
                    <p class="mb-2 font-semibold">3 requisitos del accidente de trabajo:</p>
                    <ul class="list-disc list-inside space-y-1 mb-3">
                        <li><strong>Lesión corporal:</strong> Daño físico, psíquico o mental</li>
                        <li><strong>Trabajo por cuenta ajena</strong> (o propia para autónomos)</li>
                        <li><strong>Relación de causalidad:</strong> Nexo causa-efecto entre trabajo y lesión</li>
                    </ul>
                    <p class="mb-2 font-semibold">Principales causas (datos):</p>
                    <div class="text-xs">Sobreesfuerzos (30%) → Caídas (27%) → Choques/golpes (16%) → Cortes (12%)</div>
                    <p class="mt-3 text-xs text-red-700">⚡ El AT es REPENTINO e INESPERADO (vs. enfermedad profesional que es lenta)</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-orange-500" onclick="toggleDetail('b12')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🚗</span><h3 class="text-2xl font-bold text-orange-600">13. Tipos de Accidente</h3></div>
                <p class="text-gray-600 mb-4">In itinere, en misión, presunción legal...</p>
                <div id="b12" class="hidden mt-4 text-sm text-gray-700">
                    <p class="mb-2 font-semibold text-green-600">✅ SÍ son accidentes de trabajo:</p>
                    <ul class="list-disc list-inside space-y-1 mb-3 text-xs">
                        <li><strong>In itinere:</strong> Al ir/volver del trabajo (trayecto habitual, tiempo prudencial, transporte normal)</li>
                        <li><strong>En misión:</strong> Desplazamiento por encargo de la empresa</li>
                        <li><strong>Enfermedades relacionadas:</strong> Enfermedad común causada exclusivamente por el trabajo</li>
                        <li><strong>Por presunción legal:</strong> Ocurren en tiempo y lugar de trabajo (salvo prueba contraria)</li>
                    </ul>
                    <p class="mb-2 font-semibold text-red-600">❌ NO son accidentes de trabajo:</p>
                    <ul class="list-disc list-inside space-y-1 text-xs">
                        <li><strong>Imprudencia temeraria:</strong> Asumir riesgo manifiesto, innecesario y grave</li>
                        <li><strong>Dolo:</strong> Provocar el accidente conscientemente</li>
                    </ul>
                    <p class="mt-3 text-xs text-orange-700">⚠️ Imprudencia PROFESIONAL (sin querer) → SÍ es AT. Imprudencia TEMERARIA → NO es AT</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-purple-500" onclick="toggleDetail('b13')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🦠</span><h3 class="text-2xl font-bold text-purple-600">14. Enfermedad Profesional</h3></div>
                <p class="text-gray-600 mb-4">Se desarrolla lentamente por el trabajo</p>
                <div id="b13" class="hidden mt-4 text-sm text-gray-700">
                    <div class="info-box mb-3">"La contraída a consecuencia del trabajo en las actividades del cuadro de EEPP (RD 1299/2006)" (LGSS)</div>
                    <p class="mb-2 font-semibold">2 requisitos:</p>
                    <ul class="list-disc list-inside space-y-1 mb-3">
                        <li>Trabajo por cuenta ajena o propia</li>
                        <li>Estar en el <strong>cuadro de enfermedades profesionales</strong> (RD 1299/2006)</li>
                    </ul>
                    <p class="mb-2 font-semibold">6 grupos de EEPP:</p>
                    <ol class="list-decimal list-inside space-y-1 text-xs">
                        <li>Por agentes <strong>químicos</strong> (metales, ácidos...)</li>
                        <li>Por agentes <strong>físicos</strong> (túnel carpiano, hipoacusia...) — <span class="text-red-600 font-bold">79% de los casos</span></li>
                        <li>Por agentes <strong>biológicos</strong> (hepatitis, legionela...)</li>
                        <li>Por <strong>inhalación</strong> (silicosis, asbestosis, asma...)</li>
                        <li>De la <strong>piel</strong> (polvo de madera, disolventes...)</li>
                        <li>Por agentes <strong>carcinógenos</strong> (cáncer de piel, pulmón...)</li>
                    </ol>
                    <p class="mt-3 text-xs text-purple-700">🔑 EP se desarrolla LENTAMENTE. Si no está en el cuadro pero se debe al trabajo → se trata como AT</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-gray-500" onclick="toggleDetail('b14')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">😰</span><h3 class="text-2xl font-bold text-gray-600">15. Otras Patologías</h3></div>
                <p class="text-gray-600 mb-4">Fatiga, estrés, burnout, mobbing...</p>
                <div id="b14" class="hidden mt-4 text-sm text-gray-700">
                    <ul class="list-disc list-inside space-y-2">
                        <li><strong>Fatiga:</strong> Disminución de la capacidad física y mental</li>
                        <li><strong>Estrés:</strong> Demandas del entorno superan la capacidad del trabajador</li>
                        <li><strong>Burnout:</strong> "Síndrome del quemado" — desgaste emocional (contacto con clientes)</li>
                        <li><strong>Mobbing:</strong> Presión psicológica extrema, ≥1 vez/semana durante ≥6 meses</li>
                        <li><strong>Insatisfacción laboral:</strong> Malestar que afecta al rendimiento</li>
                        <li><strong>Envejecimiento prematuro:</strong> Acelerado por altas temperaturas o esfuerzos</li>
                    </ul>
                    <p class="mt-3 text-xs text-gray-600">💡 Son patologías condicionadas por factores laborales pero NO están en el cuadro de EEPP</p>
                </div>
            </div>
        </div>

        <!-- COMPARACIÓN AT vs EP -->
        <div class="bg-gradient-to-r from-red-500 to-purple-500 text-white p-8 rounded-3xl shadow-2xl mb-12">
            <h2 class="text-3xl font-bold mb-6 text-center">⚖️ Accidente de Trabajo vs Enfermedad Profesional — Diferencias clave</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-white/20 p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3">🚑 Accidente de Trabajo</h3>
                    <p class="mb-2">Se produce de forma <strong>INESPERADA y REPENTINA</strong></p>
                    <p class="mb-2">Causa una <strong>LESIÓN TRAUMÁTICA</strong></p>
                    <p class="mb-2">Ocurre en el <strong>lugar y tiempo</strong> de trabajo</p>
                    <p class="font-mono text-sm mt-3">Ejemplo: Caída → Fractura</p>
                </div>
                <div class="bg-white/20 p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3">🦠 Enfermedad Profesional</h3>
                    <p class="mb-2">Se desarrolla de forma <strong>LENTA y PROGRESIVA</strong></p>
                    <p class="mb-2">Causa una <strong>ALTERACIÓN DE LA SALUD</strong></p>
                    <p class="mb-2">Debe estar en el <strong>cuadro de EEPP</strong> (RD 1299/2006)</p>
                    <p class="font-mono text-sm mt-3">Ejemplo: Exposición a ruido → Hipoacusia</p>
                </div>
            </div>
        </div>

        <!-- ===== SECCIÓN 4: TÉCNICAS DE PREVENCIÓN Y PROTECCIÓN ===== -->
        <div class="mb-8"><h2 class="text-2xl font-bold text-teal-700 mb-6 border-b-2 border-teal-200 pb-2">🔧 Sección 4: Técnicas de Prevención y Protección</h2></div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-12">

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-teal-500" onclick="toggleDetail('b15')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🛡️</span><h3 class="text-2xl font-bold text-teal-600">16. Técnicas de Prevención</h3></div>
                <p class="text-gray-600 mb-4">Eliminar riesgos actuando sobre las causas</p>
                <div id="b15" class="hidden mt-4 text-sm text-gray-700">
                    <div class="info-box mb-3">Prevención → actúa ANTES → elimina las CAUSAS del riesgo</div>
                    <p class="mb-2 font-semibold">5 disciplinas preventivas:</p>
                    <table class="w-full text-xs border-collapse">
                        <tr class="bg-teal-50"><th class="border p-2">Técnica</th><th class="border p-2">Finalidad</th></tr>
                        <tr><td class="border p-2 font-bold">Seguridad en el trabajo</td><td class="border p-2">Evitar ACCIDENTES laborales</td></tr>
                        <tr><td class="border p-2 font-bold">Higiene industrial</td><td class="border p-2">Prevenir ENFERMEDADES profesionales</td></tr>
                        <tr><td class="border p-2 font-bold">Ergonomía</td><td class="border p-2">Adaptar trabajo al trabajador → evitar FATIGA</td></tr>
                        <tr><td class="border p-2 font-bold">Psicosociología</td><td class="border p-2">Prevenir daños PSICOLÓGICOS</td></tr>
                        <tr><td class="border p-2 font-bold">Medicina del trabajo</td><td class="border p-2">Vigilar y mantener la SALUD</td></tr>
                    </table>
                    <p class="mt-3 text-xs text-teal-700">🎯 Orden de actuación: 1º Primaria (eliminar) → 2º Secundaria (formación) → 3º Terciaria (rehabilitar)</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-blue-500" onclick="toggleDetail('b16')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🏗️</span><h3 class="text-2xl font-bold text-blue-600">17. Protección Colectiva</h3></div>
                <p class="text-gray-600 mb-4">Protege a varias personas simultáneamente</p>
                <div id="b16" class="hidden mt-4 text-sm text-gray-700">
                    <div class="info-box mb-3">Protección colectiva → SIEMPRE antes que la individual</div>
                    <p class="mb-2 font-semibold">Sobre los LUGARES de trabajo:</p>
                    <ul class="list-disc list-inside space-y-1 mb-3 text-xs">
                        <li><strong>Redes:</strong> Minimizan efectos de caídas (obras)</li>
                        <li><strong>Ventilación:</strong> General (reduce contaminación) o localizada (en el foco)</li>
                        <li><strong>Barandillas:</strong> Impiden caídas (mínimo 90 cm de altura)</li>
                    </ul>
                    <p class="mb-2 font-semibold">Sobre los EQUIPOS de trabajo:</p>
                    <ul class="list-disc list-inside space-y-1 text-xs">
                        <li><strong>Resguardos:</strong> Barreras físicas en máquinas (vallas, tapas, carcasas)</li>
                        <li><strong>Dispositivos de prevención:</strong> Impiden funcionamiento si se detecta acceso (mando a dos manos)</li>
                        <li><strong>Interruptor diferencial:</strong> Desconecta automáticamente ante contacto eléctrico</li>
                    </ul>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-yellow-500" onclick="toggleDetail('b17')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🦺</span><h3 class="text-2xl font-bold text-yellow-600">18. EPI — Protección Individual</h3></div>
                <p class="text-gray-600 mb-4">Equipos que protegen al trabajador individualmente</p>
                <div id="b17" class="hidden mt-4 text-sm text-gray-700">
                    <div class="info-box mb-3">EPI = Equipo llevado o sujetado por el trabajador para protegerse. Marcado «CE» obligatorio. GRATUITOS.</div>
                    <table class="w-full text-xs border-collapse">
                        <tr class="bg-yellow-50"><th class="border p-2">Zona</th><th class="border p-2">EPI</th><th class="border p-2">Protegen de</th></tr>
                        <tr><td class="border p-2">🧢 Cabeza</td><td class="border p-2">Cascos de seguridad</td><td class="border p-2">Golpes, choques, proyecciones</td></tr>
                        <tr><td class="border p-2">👂 Oídos</td><td class="border p-2">Tapones, orejeras</td><td class="border p-2">Ruido excesivo</td></tr>
                        <tr><td class="border p-2">👁️ Ojos/Cara</td><td class="border p-2">Gafas, pantallas</td><td class="border p-2">Partículas, salpicaduras, radiación</td></tr>
                        <tr><td class="border p-2">😷 Vías respiratorias</td><td class="border p-2">Mascarillas, filtros</td><td class="border p-2">Atmósferas tóxicas, polvo</td></tr>
                        <tr><td class="border p-2">🧤 Manos</td><td class="border p-2">Guantes</td><td class="border p-2">Cortes, químicos, electricidad</td></tr>
                        <tr><td class="border p-2">🥾 Pies</td><td class="border p-2">Calzado de seguridad</td><td class="border p-2">Objetos, pinchazos, electricidad</td></tr>
                        <tr><td class="border p-2">🦺 Tronco</td><td class="border p-2">Chalecos, mandiles</td><td class="border p-2">Salpicaduras, chispas</td></tr>
                        <tr><td class="border p-2">🧗 Cuerpo entero</td><td class="border p-2">Arneses, chalecos reflectantes</td><td class="border p-2">Caídas, visibilidad</td></tr>
                    </table>
                    <p class="mt-3 text-xs text-yellow-700">🔑 La empresa PAGA los EPI. El trabajador DEBE usarlos correctamente.</p>
                </div>
            </div>
        </div>

        <!-- PREVENCIÓN vs PROTECCIÓN -->
        <div class="bg-gradient-to-r from-teal-500 to-blue-500 text-white p-8 rounded-3xl shadow-2xl mb-12">
            <h2 class="text-3xl font-bold mb-6 text-center">⚖️ Prevención vs Protección — ¡No son lo mismo!</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-white/20 p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3">🛡️ Prevención</h3>
                    <p class="mb-2">Actúa sobre las <strong>CAUSAS</strong> del riesgo</p>
                    <p class="mb-2">Objetivo: <strong>ELIMINAR</strong> el riesgo</p>
                    <p class="mb-2">Se aplica <strong>ANTES</strong> de que ocurra el daño</p>
                    <p class="font-mono text-sm mt-3">Ejemplo: Sustituir sustancia peligrosa por una inocua</p>
                </div>
                <div class="bg-white/20 p-6 rounded-xl">
                    <h3 class="text-xl font-bold mb-3">🦺 Protección</h3>
                    <p class="mb-2">Actúa sobre las <strong>CONSECUENCIAS</strong> del riesgo</p>
                    <p class="mb-2">Objetivo: <strong>REDUCIR</strong> el daño</p>
                    <p class="mb-2">Se aplica <strong>cuando no se puede eliminar</strong> el riesgo</p>
                    <p class="font-mono text-sm mt-3">Ejemplo: Usar casco, guantes, arnés</p>
                </div>
            </div>
            <p class="text-center mt-4 text-sm">💡 Orden: 1º Prevención → 2º Protección colectiva → 3º Protección individual (EPI)</p>
        </div>

        <!-- ===== SECCIÓN 5: SEÑALIZACIÓN ===== -->
        <div class="mb-8"><h2 class="text-2xl font-bold text-teal-700 mb-6 border-b-2 border-teal-200 pb-2">🚦 Sección 5: La Señalización de Riesgos Laborales</h2></div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-12">

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-teal-500" onclick="toggleDetail('b18')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">📢</span><h3 class="text-2xl font-bold text-teal-600">19. Tipos de Señalización</h3></div>
                <p class="text-gray-600 mb-4">4 medios de comunicación</p>
                <div id="b18" class="hidden mt-4 text-sm text-gray-700">
                    <table class="w-full text-xs border-collapse">
                        <tr class="bg-teal-50"><th class="border p-2">Tipo</th><th class="border p-2">Descripción</th></tr>
                        <tr><td class="border p-2 font-bold">📋 Señales en panel</td><td class="border p-2">Forma geométrica + color + símbolo (las más usadas)</td></tr>
                        <tr><td class="border p-2 font-bold">🔴 Luminosas</td><td class="border p-2">Luz intermitente de gran potencia</td></tr>
                        <tr><td class="border p-2 font-bold">🔊 Acústicas/Verbales</td><td class="border p-2">Señales sonoras por megafonía o voz humana</td></tr>
                        <tr><td class="border p-2 font-bold">🤚 Gestuales</td><td class="border p-2">Señales con brazos/manos codificadas</td></tr>
                    </table>
                    <p class="mt-3 text-xs text-teal-700">📌 Regulado por RD 485/1997 sobre señalización de lugares de trabajo</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-red-500" onclick="toggleDetail('b19')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🚫</span><h3 class="text-2xl font-bold text-red-600">20. Señales en Panel</h3></div>
                <p class="text-gray-600 mb-4">5 tipos según su significado</p>
                <div id="b19" class="hidden mt-4 text-sm text-gray-700">
                    <table class="w-full text-xs border-collapse">
                        <tr class="bg-red-50"><th class="border p-2">Señal</th><th class="border p-2">Forma</th><th class="border p-2">Color</th><th class="border p-2">Significado</th></tr>
                        <tr><td class="border p-2 font-bold">🔴 Prohibición</td><td class="border p-2">Círculo + barra</td><td class="border p-2">Rojo/Blanco</td><td class="border p-2">Prohíben comportamiento peligroso</td></tr>
                        <tr><td class="border p-2 font-bold">🔵 Obligación</td><td class="border p-2">Círculo</td><td class="border p-2">Azul/Blanco</td><td class="border p-2">Obligan a comportamiento de seguridad</td></tr>
                        <tr><td class="border p-2 font-bold">🟡 Advertencia</td><td class="border p-2">Triángulo</td><td class="border p-2">Amarillo/Negro</td><td class="border p-2">Advierten de riesgo o peligro</td></tr>
                        <tr><td class="border p-2 font-bold">🟥 Lucha contra incendios</td><td class="border p-2">Rectángulo</td><td class="border p-2">Rojo/Blanco</td><td class="border p-2">Ubican equipos contra incendios</td></tr>
                        <tr><td class="border p-2 font-bold">🟢 Emergencia/Salvamento</td><td class="border p-2">Rectángulo</td><td class="border p-2">Verde/Blanco</td><td class="border p-2">Salidas, primeros auxilios</td></tr>
                    </table>
                    <p class="mt-3 text-xs text-red-700">🎯 Clave test: Color ROJO → Prohibición e Incendios | AZUL → Obligación | AMARILLO → Advertencia | VERDE → Emergencia</p>
                </div>
            </div>

            <div class="concept-card bg-white rounded-2xl shadow-lg p-6 border-t-4 border-green-500" onclick="toggleDetail('b20')">
                <div class="flex items-center mb-4"><span class="text-4xl mr-3">🎯</span><h3 class="text-2xl font-bold text-green-600">21. Función de la Señalización</h3></div>
                <p class="text-gray-600 mb-4">Es complementaria, no sustituye prevención</p>
                <div id="b20" class="hidden mt-4 text-sm text-gray-700">
                    <p class="mb-2 font-semibold">La señalización sirve para:</p>
                    <ul class="list-disc list-inside space-y-2">
                        <li><strong>Llamar la atención</strong> y provocar respuesta inmediata</li>
                        <li><strong>Dar a conocer el peligro</strong> con anticipación y claridad</li>
                        <li><strong>Informar</strong> sobre el modo de actuar en cada caso</li>
                    </ul>
                    <div class="bg-green-50 p-3 rounded mt-3">
                        <p class="text-xs font-bold text-green-800">⚠️ IMPORTANTE: La señalización es una técnica COMPLEMENTARIA de la prevención y la protección. NO las sustituye. Por sí sola no elimina el riesgo.</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- OBJETIVOS -->
        <div class="bg-gradient-to-r from-green-400 to-teal-500 text-white p-8 rounded-3xl shadow-2xl mb-12">
            <h2 class="text-3xl font-bold mb-6 text-center">🎓 Al terminar esta unidad, serás capaz de:</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <div class="flex items-start"><span class="text-2xl mr-3">✅</span><p>Definir la salud según la OMS (bienestar físico, psíquico y social)</p></div>
                <div class="flex items-start"><span class="text-2xl mr-3">✅</span><p>Diferenciar prevención, riesgo laboral, factor de riesgo y daño</p></div>
                <div class="flex items-start"><span class="text-2xl mr-3">✅</span><p>Conocer la LPRL y las obligaciones de empresa y trabajador</p></div>
                <div class="flex items-start"><span class="text-2xl mr-3">✅</span><p>Clasificar los 4 grupos de factores de riesgo laboral</p></div>
                <div class="flex items-start"><span class="text-2xl mr-3">✅</span><p>Distinguir accidente de trabajo de enfermedad profesional</p></div>
                <div class="flex items-start"><span class="text-2xl mr-3">✅</span><p>Identificar los requisitos del accidente in itinere y en misión</p></div>
                <div class="flex items-start"><span class="text-2xl mr-3">✅</span><p>Conocer las 5 disciplinas preventivas y los tipos de protección</p></div>
                <div class="flex items-start"><span class="text-2xl mr-3">✅</span><p>Interpretar señales de prohibición, obligación, advertencia y emergencia</p></div>
            </div>
        </div>

        <!-- RECORDATORIOS -->
        <div class="bg-white rounded-2xl shadow-lg p-8 mb-12">
            <h3 class="text-2xl font-bold text-gray-800 mb-6 text-center">⚡ Recordatorios Importantes para el Examen</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-yellow-50 border-l-4 border-yellow-400 p-4">
                    <p class="text-yellow-800 font-semibold mb-2">📌 Salud según la OMS</p>
                    <p class="text-sm text-yellow-700">No es solo "no estar enfermo". Es un estado de <strong>completo bienestar FÍSICO, PSÍQUICO y SOCIAL</strong>. Pregunta clásica de test.</p>
                </div>
                <div class="bg-red-50 border-l-4 border-red-400 p-4">
                    <p class="text-red-800 font-semibold mb-2">⚠️ AT vs EP: ¡No confundir!</p>
                    <p class="text-sm text-red-700">• AT → Repentino, lesión traumática<br>• EP → Lenta, está en el cuadro RD 1299/2006<br>• Si la enfermedad NO está en el cuadro pero se debe al trabajo → se trata como AT</p>
                </div>
                <div class="bg-blue-50 border-l-4 border-blue-400 p-4">
                    <p class="text-blue-800 font-semibold mb-2">🎯 Orden de actuación obligatorio</p>
                    <p class="text-sm text-blue-700">1º <strong>Prevención</strong> (eliminar riesgo)<br>2º <strong>Protección colectiva</strong> (redes, barandillas...)<br>3º <strong>Protección individual</strong> (EPI)<br>Nunca al revés.</p>
                </div>
                <div class="bg-green-50 border-l-4 border-green-400 p-4">
                    <p class="text-green-800 font-semibold mb-2">💡 Vigilancia de la salud</p>
                    <p class="text-sm text-green-700">• Es <strong>VOLUNTARIA</strong> para el trabajador (en general)<br>• Excepciones: si es imprescindible para evaluar efectos del puesto, si el trabajador puede ser peligroso, o en actividades de especial riesgo<br>• Siempre <strong>GRATUITA</strong> y en tiempo de trabajo</p>
                </div>
                <div class="bg-purple-50 border-l-4 border-purple-400 p-4">
                    <p class="text-purple-800 font-semibold mb-2">🔑 Accidente in itinere — 4 requisitos</p>
                    <p class="text-sm text-purple-700">1. Finalidad del viaje: ir/volver del trabajo<br>2. Trayecto habitual (no el más corto necesariamente)<br>3. Tiempo prudencial, sin desvíos relevantes<br>4. Medio de transporte normal/idóneo</p>
                </div>
                <div class="bg-orange-50 border-l-4 border-orange-400 p-4">
                    <p class="text-orange-800 font-semibold mb-2">📋 Señales — Colores clave</p>
                    <p class="text-sm text-orange-700">🔴 <strong>Rojo</strong> = Prohibición + Incendios<br>🔵 <strong>Azul</strong> = Obligación<br>🟡 <strong>Amarillo</strong> = Advertencia (triángulo)<br>🟢 <strong>Verde</strong> = Salvamento / Emergencia</p>
                </div>
            </div>
        </div>

        <!-- INSTRUCCIONES -->
        <div class="bg-white rounded-2xl shadow-lg p-8 text-center">
            <h3 class="text-2xl font-bold text-gray-800 mb-4">💡 Cómo usar este mapa</h3>
            <p class="text-gray-600 mb-4"><strong>Haz clic en cada tarjeta</strong> para desplegar los detalles, definiciones legales y datos clave. Esta unidad es <strong>fundamental</strong> para obtener el título de Técnico Básico en PRL (50 horas).</p>
            <div class="mt-6 bg-teal-50 border-l-4 border-teal-400 p-4">
                <p class="text-teal-800">🌟 <strong>Consejo:</strong> Presta especial atención a las diferencias AT/EP, los 4 grupos de factores de riesgo y el orden prevención → protección colectiva → EPI. Son los puntos que más caen en examen. <em>¡A por ello!</em></p>
            </div>
        </div>

        <div class="mt-12 text-center text-gray-500 text-sm">
            <p>🛡️ Unidad 1 — La Prevención de Riesgos Laborales y la Salud Laboral | DAM — Universidad Europea de Madrid</p>
            <p class="mt-2">¡A trabajar seguro! 💪</p>
        </div>
    </div>

    <script>
        function toggleDetail(id) {
            const element = document.getElementById(id);
            if (element.classList.contains('hidden')) {
                element.classList.remove('hidden');
                element.classList.add('animate-pulse-soft');
            } else {
                element.classList.add('hidden');
                element.classList.remove('animate-pulse-soft');
            }
        }
    </script>
</body>
</html>
