<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROI-360 | Infográfico de Tráfego Pago para Salões de Beleza</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-datalabels@2.0.0"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            height: 320px;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
        .flow-arrow::after {
            content: '▼';
            font-size: 2rem;
            color: #60A5FA;
            margin-top: 0.5rem;
            margin-bottom: 0.5rem;
        }
         .flow-arrow-h::after {
            content: '▶';
            font-size: 2rem;
            color: #60A5FA;
            margin: 0 1rem;
        }
        .gradient-bg {
            background: linear-gradient(180deg, #1A202C 0%, #2D3748 100%);
        }
        .section-gradient-box {
            background: linear-gradient(135deg, #2D3748 0%, #1A202C 100%);
            border-radius: 1.5rem;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.5), 0 10px 10px -5px rgba(0, 0, 0, 0.4);
            margin-left: auto;
            margin-right: auto;
            max-width: 100%;
        }
        .strong-shadow-box {
            box-shadow: 0px 10px 40px rgba(0, 0, 0, 1), 0px 20px 60px rgba(0, 0, 0, 0.8);
            background-color: #2D3748;
        }
        .icon-highlight {
            font-size: 4.5rem;
            color: #4CAF50;
            margin-bottom: 0.75rem;
            text-shadow: 0px 0px 20px rgba(0, 0, 0, 1), 0px 0px 30px rgba(0, 0, 0, 0.8);
        }
        .title-shadow {
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .chart-contour {
            border: 2px solid black;
            box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.5);
        }

        @media print {
            .pdf-page-break-after {
                page-break-after: always;
            }
            .chart-container {
                width: 100% !important;
                max-width: 500px !important;
                height: 350px !important;
                margin: 0 auto !important;
            }
            .chart-container canvas {
                width: 100% !important;
                height: 100% !important;
            }
        }
    </style>
</head>
<body class="bg-[#1A202C] text-gray-200">
    <main class="container mx-auto p-4 md:p-8">
        <!-- HEADER -->
        <header class="text-center py-8">
            <div class="section-gradient-box p-8 max-w-4xl pdf-page-break-after">
                <h1 class="text-5xl md:text-7xl font-bold text-[#4CAF50] leading-tight mb-4 title-shadow">Prestação de Serviços da ROI-360</h1>
                <p class="text-xl md:text-2xl text-white max-w-4xl mx-auto mb-4 title-shadow">
                    <b>Desvende o segredo dos salões de elite!</b> Conquiste uma agenda cheia e um faturamento que você sempre sonhou, transformando seu investimento em <b>lucro real</b>.
                </p>
                <h1 class="text-4xl md:text-6xl font-bold text-white mb-4 title-shadow">Transforme Cliques em Clientes</h1>
                <p class="text-lg md:text-xl text-white max-w-3xl mx-auto mb-4 title-shadow">
                    Uma análise visual da nossa estratégia de Tráfego Pago, desenhada para lotar a agenda do seu salão de beleza.
                </p>
                <div class="rounded-xl p-8 text-center strong-shadow-box">
                    <h2 class="text-2xl font-semibold text-[#4CAF50] mb-2 title-shadow">O Potencial de Retorno</h2>
                    <p class="text-white mb-4 title-shadow">Nossa meta é clara: maximizar seu Retorno Sobre o Investimento (ROI). Uma estratégia bem executada pode gerar resultados exponenciais.</p>
                    <div class="text-7xl font-bold text-[#4CAF50]">
                        360%+
                    </div>
                    <p class="text-white mt-2 title-shadow">de ROI Potencial em 6 meses</p>
                </div>
            </div>
        </header>
        <!-- SECTIONS -->
        <section class="py-8">
            <div class="section-gradient-box p-8 max-w-4xl pdf-page-break-after">
                <h2 class="text-3xl font-bold text-[#4CAF50] mb-4 title-shadow">1° Visão 360° do Sucesso</h2>
                <p class="text-white mt-2 max-w-2xl mx-auto mb-8 title-shadow">Tudo começa com uma fundação sólida. Entendemos seu negócio a fundo para criar campanhas que realmente funcionam.</p>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-6 justify-items-center mx-auto">
                    <div class="p-6 rounded-lg strong-shadow-box w-full">
                        <div class="icon-highlight">🔎</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">Análise do Salão e Mercado</h3>
                        <p class="text-sm text-white mt-2 title-shadow">Mergulhamos no seu salão para descobrir seu brilho único e mapear o caminho até clientes apaixonadas.</p>
                    </div>
                    <div class="p-6 rounded-lg strong-shadow-box w-full">
                        <div class="icon-highlight">🎯</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">Definição da Persona Ideal</h3>
                        <p class="text-sm text-white mt-2 title-shadow">Identificamos sua cliente dos sonhos para direcionar anúncios que geram agendamentos reais e qualificadas.</p>
                    </div>
                    <div class="p-6 rounded-lg strong-shadow-box w-full">
                        <div class="icon-highlight">🚀</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">ROI Máximo de Campanhas 360</h3>
                        <p class="text-sm text-white mt-2 title-shadow">Definimos o posicionamento que te destaca, atraindo clientes que valorizam e pagam pelo seu serviço.</p>
                    </div>
                    <div class="p-6 rounded-lg strong-shadow-box w-full">
                        <div class="icon-highlight">📊</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">Relatórios Atualizados</h3>
                        <p class="text-sm text-white mt-2 title-shadow">Receba insights claros e práticos para otimizar suas estratégias e ver o impacto direto no seu faturamento.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="py-8">
            <div class="section-gradient-box p-8 max-w-4xl pdf-page-break-after">
                <h2 class="text-3xl font-bold text-[#4CAF50] mb-4 px-4 title-shadow">2° Aceleração Digital</h2>
                <p class="text-white mt-2 max-w-2xl mx-auto mb-8 px-4 title-shadow">Criamos anúncios que não apenas alcançam, mas encantam e convertem seu público-alvo.</p>
                <div class="grid grid-cols-2 gap-6 items-center px-4">
                    <div class="p-6 rounded-xl strong-shadow-box">
                        <h3 class="text-xl font-semibold text-white text-center mb-4 title-shadow">Eficácia por Formato de Anúncio</h3>
                        <p class="text-white text-center text-sm mb-4 title-shadow">Analisamos e priorizamos os formatos que mais geram agendamentos para salões, como vídeos de transformação e carrosséis de resultados.</p>
                        <div class="chart-container">
                            <canvas id="adFormatChart" class="chart-contour"></canvas>
                        </div>
                    </div>
                    <div class="p-6 rounded-xl strong-shadow-box">
                        <h3 class="text-xl font-semibold text-white text-center mb-4 title-shadow">Investimento Mensal Médio</h3>
                         <p class="text-white text-center text-sm mb-4 title-shadow">A maior parte do seu investimento vai diretamente para os anúncios, com uma parcela dedicada à nossa gestão estratégica e otimização contínua.</p>
                        <div class="chart-container">
                            <canvas id="investmentChart" class="chart-contour"></canvas>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="py-8">
            <div class="section-gradient-box p-8 max-w-4xl pdf-page-break-after">
                <h2 class="text-3xl font-bold text-[#4CAF50] mb-4 title-shadow">3° Performance em Evolução</h2>
                <p class="text-white mt-2 max-w-2xl mx-auto mb-8 title-shadow">Nosso trabalho não para. Monitoramos e ajustamos suas campanhas semanalmente para reduzir custos e maximizar resultados.</p>
                <div class="rounded-xl strong-shadow-box md:col-span-2 p-6">
                    <h3 class="text-xl font-semibold text-white text-center mb-4 title-shadow">Otimização Inteligente: Seu Lucro Garantido!</h3>
                    <p class="text-white text-center text-sm mb-4 title-shadow">Nossa estratégia foca em <b>reduzir drasticamente seu custo de aquisição por cliente</b>, transformando cada investimento em um lucro maior para o seu salão. Veja como a otimização contínua impacta seu bolso:</p>
                    <div class="chart-container" style="max-width: 800px;">
                        <canvas id="optimizationChart"></canvas>
                    </div>
                </div>
            </div>
        </section>
        <section class="py-8">
            <div class="section-gradient-box p-8 max-w-4xl pdf-page-break-after">
                <h2 class="text-3xl font-bold text-[#4CAF50] mb-4 title-shadow">4° Alcance Direto e Visibilidade</h2>
                <p class="text-white mt-2 max-w-2xl mx-auto mb-8 title-shadow">Potencialize sua agenda e seguidores com campanhas focadas em conexão e crescimento para seu salão.</p>
                <div class="flex flex-row items-center justify-center text-center gap-4 flex-wrap px-4">
                    <div class="p-6 rounded-lg strong-shadow-box w-full sm:w-2/5 md:w-1/3">
                        <div class="icon-highlight">📲</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">WhatsApp que Vende!</h3>
                        <p class="text-sm text-white mt-2 title-shadow">Conecte-se instantaneamente com potenciais clientes e transforme conversas em agendamentos diretos e eficazes.</p>
                    </div>
                    <div class="p-6 rounded-lg strong-shadow-box w-full sm:w-2/5 md:w-1/3">
                        <div class="icon-highlight">🌟</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">Perfil Magnético no Instagram!</h3>
                        <p class="text-sm text-white mt-2 title-shadow">Aumente sua visibilidade e atraia seguidores qualificados, transformando curiosos em uma comunidade engajada e fiel ao seu salão.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="py-8 text-center">
            <div class="section-gradient-box p-8 max-w-4xl pdf-page-break-after">
                <h2 class="text-3xl font-bold text-[#4CAF50] mb-8 title-shadow">Seu Investimento Transparente</h2>
                <p class="text-white mt-2 max-w-2xl mx-auto mb-8 title-shadow">Clareza e controle total sobre seus custos.</p>
                <div class="flex flex-row justify-center items-stretch gap-8 flex-wrap">
                    <div class="p-8 rounded-lg strong-shadow-box flex-1 min-w-[300px]">
                        <div class="icon-highlight">📈</div>
                        <h3 class="text-2xl font-bold text-white title-shadow">Gestão ROI-360</h3>
                        <p class="text-5xl font-bold text-[#4CAF50] mt-2">R$ 1.900</p>
                        <p class="font-semibold text-white title-shadow">/mês</p>
                        <p class="text-xl font-bold text-[#4CAF50] mt-4">
                            OFERTA RELÂMPAGO!
                        </p>
                        <p class="text-3xl font-bold text-[#4CAF50]">
                            APENAS R$ 1.500/mês
                        </p>
                        <p class="text-lg text-white mt-1 title-shadow">
                            Válido para fechamentos <b>SOMENTE EM 27/06/2024!</b>
                        </p>
                    </div>
                    <div class="p-8 rounded-lg strong-shadow-box flex-1 min-w-[300px]">
                        <div class="icon-highlight">💰</div>
                        <h3 class="text-2xl font-bold text-white title-shadow">Seu Orçamento de Anúncios</h3>
                        <p class="text-5xl font-bold text-[#4CAF50] mt-2">R$ 20-30<span class="font-semibold text-white title-shadow">/dia</span></p>
                    </div>
                </div>
            </div>
        </section>
        <section class="py-8">
             <div class="section-gradient-box p-8 max-w-4xl pdf-page-break-after">
                 <h2 class="text-3xl font-bold text-[#4CAF50] mb-12 title-shadow">Estratégias Adicionais Inclusas</h2>
                 <p class="text-white mt-2 max-w-2xl mx-auto mb-8 title-shadow">Vamos além do tráfego pago, fortalecendo sua marca como um todo.</p>
                 <div class="flex flex-row items-center justify-center text-center gap-4 flex-wrap px-4">
                     <div class="p-6 rounded-lg strong-shadow-box w-full sm:w-2/5 md:w-1/3">
                         <div class="icon-highlight">📸</div>
                         <h3 class="font-semibold text-[#4CAF50] title-shadow">Consultoria para Stories</h3>
                         <p class="text-sm text-white mt-2 title-shadow">Transforme seus stories em um ímã de clientes, com dicas práticas e naturais.</p>
                     </div>
                     <div class="p-6 rounded-lg strong-shadow-box w-full sm:w-2/5 md:w-1/3">
                          <div class="icon-highlight">✍️</div>
                         <h3 class="font-semibold text-[#4CAF50] title-shadow">Sugestão de Conteúdos</h3>
                         <p class="text-sm text-white mt-2 title-shadow">Descubra os temas que geram mais engajamento e agendamentos para o seu salão.</p>
                     </div>
                     <div class="p-6 rounded-lg strong-shadow-box w-full sm:w-2/5 md:w-1/3">
                          <div class="icon-highlight">⭐</div>
                         <h3 class="font-semibold text-[#4CAF50] title-shadow">Uso de Depoimentos</h3>
                         <p class="text-sm text-white mt-2 title-shadow">Aprenda a transformar a satisfação de suas clientes em prova social poderosa.</p>
                     </div>
                 </div>
             </div>
        </section>
        <section class="py-8">
            <div class="section-gradient-box p-8 max-w-4xl">
                <h2 class="text-4xl font-bold text-[#4CAF50] mb-4 flex items-center justify-center title-shadow">
                    <span class="icon-highlight mr-4">🎁</span> Bônus Especial
                </h2>
                <p class="text-lg text-white max-w-3xl mx-auto mb-8 title-shadow">
                    Transforme seu salão em um fenômeno online com vídeos VEO3 que capturam olhares e convertem visitas em agendamentos. A imagem que seu público vê é a chave para o sucesso!
                </p>
                <div class="flex flex-row items-center justify-center text-center gap-4 flex-wrap px-4">
                    <div class="p-6 rounded-xl strong-shadow-box w-full sm:w-2/5 md:w-1/3">
                        <div class="icon-highlight">📝</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">Roteiro Persuasivo</h3>
                        <p class="text-gray-400 text-sm mt-2">Criação de roteiros que capturam a atenção e direcionam à ação.</p>
                    </div>
                    <div class="p-6 rounded-xl strong-shadow-box w-full sm:w-2/5 md:w-1/3">
                        <div class="icon-highlight">✨</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">Produção Otimizada VEO3</h3>
                        <p class="text-gray-400 text-sm mt-2">Vídeos curtos e dinâmicos, perfeitos para a performance em anúncios.</p>
                    </div>
                    <div class="p-6 rounded-xl strong-shadow-box w-full sm:w-2/5 md:w-1/3">
                        <div class="icon-highlight">📈</div>
                        <h3 class="font-semibold text-[#4CAF50] title-shadow">Foco na Conversão</h3>
                        <p class="text-gray-400 text-sm mt-2">Elements visuais e textuais pensados para gerar agendamentos.</p>
                    </div>
                </div>
            </div>
        </section>
    </main>
    <script>
        window.addEventListener('DOMContentLoaded', () => {
            function wrapLabels(label, maxWidth) {
                const words = label.split(' ');
                const lines = [];
                let currentLine = '';
                for (const word of words) {
                    if ((currentLine + word).length <= maxWidth) {
                        currentLine += `${word} `;
                    } else {
                        lines.push(currentLine.trim());
                        currentLine = `${word} `;
                    }
                }
                lines.push(currentLine.trim());
                return lines;
            }

            const tooltipTitleCallback = (tooltipItems) => {
                const item = tooltipItems[0];
                let label = item.chart.data.labels[item.dataIndex];
                if (Array.isArray(label)) {
                    return label.join(' ');
                }
                return label;
            };
            
            const commonChartOptions = {
                maintainAspectRatio: false,
                responsive: true,
                plugins: {
                    legend: {
                        labels: {
                            color: '#FFFFFF',
                            font: {
                                size: 14
                            }
                        }
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    },
                    datalabels: {
                        color: '#FFFFFF',
                        font: {
                            size: 12,
                            weight: 'bold'
                        },
                        formatter: (value, context) => {
                            if (context.chart.canvas.id === 'investmentChart') {
                                const total = context.chart.data.datasets[0].data.reduce((a, b) => a + b, 0);
                                const percentage = Math.round((value / total) * 100) + '%';
                                return value + ' (' + percentage + ')';
                            }
                            return value;
                        },
                        textShadowBlur: 5,
                        textShadowColor: 'rgba(0, 0, 0, 0.9)'
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        grid: {
                            color: 'rgba(255, 255, 255, 0.1)'
                        },
                        ticks: {
                            color: '#F7FAFC'
                        }
                    },
                    x: {
                        grid: {
                            display: false
                        },
                        ticks: {
                            color: '#F7FAFC'
                        }
                    }
                }
            };

            Chart.register(ChartDataLabels);

            const adFormatCtx = document.getElementById('adFormatChart').getContext('2d');
            new Chart(adFormatCtx, {
                type: 'bar',
                data: {
                    labels: ['Vídeo de Transformação', 'Antes e Depois', 'Carrossel de Resultados', wrapLabels('Depoimento de Cliente', 16), 'Imagem Única'],
                    datasets: [{
                        label: 'Nível de Engajamento',
                        data: [95, 92, 85, 88, 70],
                        backgroundColor: ['#4CAF50', '#7FFF00', '#00FFFF', '#FFD700', '#FF4500'],
                        borderColor: '#1A202C',
                        borderWidth: 2,
                        borderRadius: 5
                    }]
                },
                options: {
                    ...commonChartOptions,
                    plugins: {
                        legend: { display: false },
                        tooltip: { enabled: false },
                        datalabels: {
                            anchor: 'end',
                            align: 'top',
                            color: '#FFFFFF',
                            textShadowBlur: 5,
                            textShadowColor: 'rgba(0, 0, 0, 0.9)'
                        }
                    },
                    scales: {
                        x: {
                            grid: {
                                display: false
                            },
                            ticks: {
                                color: '#FFFFFF',
                                autoSkip: false,
                                maxRotation: 45,
                                minRotation: 45,
                                font: {
                                    size: 10
                                }
                            }
                        },
                        y: commonChartOptions.scales.y
                    }
                }
            });

            const investmentCtx = document.getElementById('investmentChart').getContext('2d');
            new Chart(investmentCtx, {
                type: 'doughnut',
                data: {
                    labels: ['Orçamento de Anúncios (Facebook/Instagram)', 'Gestão e Otimização ROI-360'],
                    datasets: [{
                        label: 'Investimento Médio',
                        data: [750, 1900],
                        backgroundColor: ['#32CD32', '#FFD700'],
                        borderColor: '#2D3748',
                        borderWidth: 4,
                    }]
                },
                options: {
                    maintainAspectRatio: false,
                    responsive: true,
                    plugins: {
                        legend: {
                            position: 'bottom',
                            labels: {
                                color: '#FFFFFF',
                                font: { size: 12 },
                                boxWidth: 20
                            }
                        },
                        tooltip: { enabled: false },
                        datalabels: {
                            formatter: (value, context) => {
                                const total = context.chart.data.datasets[0].data.reduce((a, b) => a + b, 0);
                                const percentage = Math.round((value / total) * 100);
                                return percentage > 5 ? percentage + '%' : '';
                            },
                            color: '#FFFFFF',
                            textShadowBlur: 5,
                            textShadowColor: 'rgba(0, 0, 0, 0.9)'
                        }
                    }
                }
            });

            const optimizationCtx = document.getElementById('optimizationChart').getContext('2d');
            new Chart(optimizationCtx, {
                type: 'line',
                data: {
                    labels: ['Mês 1', 'Mês 2', 'Mês 3', 'Mês 4'],
                    datasets: [{
                        label: 'Custo de Clientes (R$)',
                        data: [10.00, 5.00, 2.00, 0.65], /* Dados ajustados */
                        fill: true,
                        backgroundColor: 'rgba(78, 205, 196, 0.2)',
                        borderColor: '#4ECDC4',
                        tension: 0.3,
                        pointBackgroundColor: '#FFFFFF',
                        pointBorderColor: '#4ECDC4',
                        pointHoverRadius: 7,
                        pointRadius: 5,
                    }]
                },
                options: {
                    ...commonChartOptions,
                    plugins: {
                        legend: { display: true },
                        tooltip: { enabled: false },
                        datalabels: {
                            align: 'end',
                            anchor: 'end',
                            formatter: (value) => `R$ ${value.toFixed(2)}`,
                            color: '#FFFFFF',
                            textShadowBlur: 5,
                            textShadowColor: 'rgba(0, 0, 0, 0.9)'
                        }
                    }
                }
            });
        });
    </script>
</body>
</html>
