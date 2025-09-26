<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Costos - Producción de Jugos</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(45deg, #ff6b35, #f9ca24);
            color: white;
            padding: 30px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        .header p {
            font-size: 1.2em;
            opacity: 0.9;
        }
        
        .calculator-body {
            display: grid;
            grid-template-columns: 1fr 400px;
            gap: 0;
            min-height: 600px;
        }
        
        .input-section {
            padding: 40px;
            background: #f8f9fa;
        }
        
        .results-section {
            background: linear-gradient(180deg, #2c3e50, #3498db);
            color: white;
            padding: 40px;
            position: sticky;
            top: 0;
            height: fit-content;
        }
        
        .section-title {
            color: #2c3e50;
            font-size: 1.4em;
            margin: 30px 0 20px 0;
            border-bottom: 3px solid #3498db;
            padding-bottom: 10px;
        }
        
        .section-title:first-of-type {
            margin-top: 0;
        }
        
        .input-group {
            margin-bottom: 20px;
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: transform 0.2s ease;
        }
        
        .input-group:hover {
            transform: translateY(-2px);
        }
        
        .input-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 15px;
        }
        
        .input-row:last-child {
            margin-bottom: 0;
        }
        
        .input-full {
            display: block;
            width: 100%;
        }
        
        label {
            display: block;
            font-weight: bold;
            color: #555;
            margin-bottom: 8px;
            font-size: 0.95em;
        }
        
        input[type="number"], input[type="text"] {
            width: 100%;
            padding: 12px 15px;
            border: 2px solid #e1e8ed;
            border-radius: 8px;
            font-size: 1em;
            transition: all 0.3s ease;
            background: #f8f9fa;
        }
        
        input[type="number"]:focus, input[type="text"]:focus {
            outline: none;
            border-color: #3498db;
            background: white;
            box-shadow: 0 0 10px rgba(52, 152, 219, 0.2);
        }
        
        .result-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
            border-bottom: 1px solid rgba(255,255,255,0.2);
            font-size: 1.1em;
        }
        
        .result-item:last-child {
            border-bottom: none;
            font-size: 1.3em;
            font-weight: bold;
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        
        .result-value {
            font-weight: bold;
            color: #f39c12;
        }
        
        .final-result .result-value {
            color: #2ecc71;
            font-size: 1.2em;
        }
        
        .currency {
            color: #95a5a6;
            font-size: 0.9em;
        }
        
        .calculate-btn {
            background: linear-gradient(45deg, #e74c3c, #c0392b);
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 1.2em;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(231, 76, 60, 0.3);
            margin: 30px auto;
            display: block;
        }
        
        .calculate-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(231, 76, 60, 0.4);
        }
        
        .info-text {
            color: #7f8c8d;
            font-size: 0.85em;
            margin-top: 5px;
            font-style: italic;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🧃 Calculadora de Costos</h1>
            <p>Producción de Jugos - Todas las Presentaciones</p>
        </div>
        
        <div class="calculator-body">
            <div class="input-section">
                <form id="costForm">
                    <h2 class="section-title">📋 Información del Producto</h2>
                    <div class="input-group">
                        <div class="input-row">
                            <div>
                                <label for="productName">Nombre del Producto:</label>
                                <input type="text" id="productName" placeholder="Ej: Jugo de Naranja 500ml">
                            </div>
                            <div>
                                <label for="batchSize">Tamaño del Lote (unidades):</label>
                                <input type="number" id="batchSize" value="1000" min="1">
                            </div>
                        </div>
                    </div>

                    <h2 class="section-title">👥 Mano de Obra Directa</h2>
                    <div class="input-group">
                        <div class="input-row">
                            <div>
                                <label for="laborHours">Horas-persona por lote:</label>
                                <input type="number" id="laborHours" value="8" step="0.1" min="0">
                                <div class="info-text">Tiempo total de personal directo</div>
                            </div>
                            <div>
                                <label for="hourlyRate">Costo por hora (MXN):</label>
                                <input type="number" id="hourlyRate" value="50" step="0.01" min="0">
                                <div class="info-text">Incluye salario base</div>
                            </div>
                        </div>
                        <div class="input-row">
                            <div>
                                <label for="benefits">Prestaciones (%):</label>
                                <input type="number" id="benefits" value="35" step="0.1" min="0" max="100">
                                <div class="info-text">IMSS, aguinaldo, vacaciones, etc.</div>
                            </div>
                            <div>
                                <label for="extraHours">Horas extra (%):</label>
                                <input type="number" id="extraHours" value="0" step="0.1" min="0">
                                <div class="info-text">Porcentaje de horas extra</div>
                            </div>
                        </div>
                    </div>

                    <h2 class="section-title">🥤 Materia Prima</h2>
                    <div class="input-group">
                        <div class="input-full">
                            <label for="totalMaterialCost">Costo total de materia prima por lote (MXN):</label>
                            <input type="number" id="totalMaterialCost" value="925" step="0.01" min="0">
                            <div class="info-text">Incluye fruta/pulpa, azúcar, agua, conservantes, envases, etiquetas y merma</div>
                        </div>
                    </div>

                    <h2 class="section-title">⚡ Costos de Infraestructura</h2>
                    <div class="input-group">
                        <div class="input-row">
                            <div>
                                <label for="electricityHour">Consumo eléctrico (kWh/hora):</label>
                                <input type="number" id="electricityHour" value="15" step="0.1" min="0">
                            </div>
                            <div>
                                <label for="electricityRate">Costo por kWh (MXN):</label>
                                <input type="number" id="electricityRate" value="3.5" step="0.01" min="0">
                            </div>
                        </div>
                        <div class="input-row">
                            <div>
                                <label for="waterUsage">Agua/limpieza por lote (litros):</label>
                                <input type="number" id="waterUsage" value="500" step="1" min="0">
                                <div class="info-text">Limpieza y procesos</div>
                            </div>
                            <div>
                                <label for="waterRate">Costo por litro (MXN):</label>
                                <input type="number" id="waterRate" value="0.02" step="0.001" min="0">
                            </div>
                        </div>
                        <div class="input-row">
                            <div>
                                <label for="gasCost">Gas/combustible por lote (MXN):</label>
                                <input type="number" id="gasCost" value="50" step="0.01" min="0">
                            </div>
                            <div>
                                <label for="productionHours">Horas de producción por lote:</label>
                                <input type="number" id="productionHours" value="6" step="0.1" min="0">
                            </div>
                        </div>
                    </div>

                    <h2 class="section-title">🔧 Depreciación y Mantenimiento</h2>
                    <div class="input-group">
                        <div class="input-row">
                            <div>
                                <label for="machineCost">Valor maquinaria (MXN):</label>
                                <input type="number" id="machineCost" value="500000" step="1000" min="0">
                                <div class="info-text">Valor total del equipo</div>
                            </div>
                            <div>
                                <label for="machineLife">Vida útil (años):</label>
                                <input type="number" id="machineLife" value="10" step="1" min="1">
                            </div>
                        </div>
                        <div class="input-row">
                            <div>
                                <label for="hoursPerYear">Horas uso por año:</label>
                                <input type="number" id="hoursPerYear" value="2000" step="1" min="1">
                                <div class="info-text">Horas operación anual</div>
                            </div>
                            <div>
                                <label for="maintenance">Mantenimiento mensual (MXN):</label>
                                <input type="number" id="maintenance" value="5000" step="100" min="0">
                            </div>
                        </div>
                    </div>

                    <h2 class="section-title">📊 Costos Indirectos</h2>
                    <div class="input-group">
                        <div class="input-row">
                            <div>
                                <label for="supervision">Supervisión/control (%):</label>
                                <input type="number" id="supervision" value="8" step="0.1" min="0">
                                <div class="info-text">% sobre costo directo</div>
                            </div>
                            <div>
                                <label for="quality">Control de calidad (MXN/lote):</label>
                                <input type="number" id="quality" value="100" step="1" min="0">
                            </div>
                        </div>
                        <div class="input-row">
                            <div>
                                <label for="cleaning">Limpieza/sanitización (MXN/lote):</label>
                                <input type="number" id="cleaning" value="80" step="1" min="0">
                            </div>
                            <div>
                                <label for="admin">Gastos administrativos (%):</label>
                                <input type="number" id="admin" value="12" step="0.1" min="0">
                                <div class="info-text">% sobre costo total</div>
                            </div>
                        </div>
                    </div>

                    <button type="button" class="calculate-btn" onclick="calculateCosts()">
                        🧮 Calcular Costos
                    </button>
                </form>
            </div>

            <div class="results-section">
                <h2 style="margin-bottom: 30px; font-size: 1.8em;">💰 Resultados</h2>
                
                <div class="result-item">
                    <span>Mano de Obra Total:</span>
                    <span class="result-value" id="laborTotal">$0.00 <span class="currency">MXN</span></span>
                </div>
                
                <div class="result-item">
                    <span>Materia Prima Total:</span>
                    <span class="result-value" id="materialTotal">$0.00 <span class="currency">MXN</span></span>
                </div>
                
                <div class="result-item">
                    <span>Infraestructura:</span>
                    <span class="result-value" id="infraTotal">$0.00 <span class="currency">MXN</span></span>
                </div>
                
                <div class="result-item">
                    <span>Depreciación:</span>
                    <span class="result-value" id="depreciationTotal">$0.00 <span class="currency">MXN</span></span>
                </div>
                
                <div class="result-item">
                    <span>Costos Indirectos:</span>
                    <span class="result-value" id="indirectTotal">$0.00 <span class="currency">MXN</span></span>
                </div>
                
                <div class="result-item final-result">
                    <span>COSTO TOTAL POR LOTE:</span>
                    <span class="result-value" id="totalCost">$0.00 <span class="currency">MXN</span></span>
                </div>
                
                <div class="result-item final-result">
                    <span>COSTO POR UNIDAD:</span>
                    <span class="result-value" id="unitCost">$0.00 <span class="currency">MXN</span></span>
                </div>

                <div style="margin-top: 30px; padding: 20px; background: rgba(255,255,255,0.1); border-radius: 10px;">
                    <h3 style="margin-bottom: 15px; color: #f39c12;">📈 Recomendaciones de Precio</h3>
                    <div class="result-item" style="border-bottom: 1px solid rgba(255,255,255,0.2); padding: 10px 0;">
                        <span>Precio sugerido (+30%):</span>
                        <span class="result-value" id="suggestedPrice30">$0.00</span>
                    </div>
                    <div class="result-item" style="border-bottom: 1px solid rgba(255,255,255,0.2); padding: 10px 0;">
                        <span>Precio competitivo (+50%):</span>
                        <span class="result-value" id="suggestedPrice50">$0.00</span>
                    </div>
                    <div class="result-item" style="border-bottom: none; padding: 10px 0;">
                        <span>Precio premium (+80%):</span>
                        <span class="result-value" id="suggestedPrice80">$0.00</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function calculateCosts() {
            // Obtener todos los valores
            const batchSize = parseFloat(document.getElementById('batchSize').value) || 1;
            
            // Mano de obra
            const laborHours = parseFloat(document.getElementById('laborHours').value) || 0;
            const hourlyRate = parseFloat(document.getElementById('hourlyRate').value) || 0;
            const benefits = parseFloat(document.getElementById('benefits').value) || 0;
            const extraHours = parseFloat(document.getElementById('extraHours').value) || 0;
            
            // Materia prima (ahora simplificado)
            const totalMaterialCost = parseFloat(document.getElementById('totalMaterialCost').value) || 0;
            
            // Infraestructura
            const electricityHour = parseFloat(document.getElementById('electricityHour').value) || 0;
            const electricityRate = parseFloat(document.getElementById('electricityRate').value) || 0;
            const waterUsage = parseFloat(document.getElementById('waterUsage').value) || 0;
            const waterRate = parseFloat(document.getElementById('waterRate').value) || 0;
            const gasCost = parseFloat(document.getElementById('gasCost').value) || 0;
            const productionHours = parseFloat(document.getElementById('productionHours').value) || 0;
            
            // Depreciación
            const machineCost = parseFloat(document.getElementById('machineCost').value) || 0;
            const machineLife = parseFloat(document.getElementById('machineLife').value) || 1;
            const hoursPerYear = parseFloat(document.getElementById('hoursPerYear').value) || 1;
            const maintenance = parseFloat(document.getElementById('maintenance').value) || 0;
            
            // Costos indirectos
            const supervision = parseFloat(document.getElementById('supervision').value) || 0;
            const quality = parseFloat(document.getElementById('quality').value) || 0;
            const cleaning = parseFloat(document.getElementById('cleaning').value) || 0;
            const admin = parseFloat(document.getElementById('admin').value) || 0;
            
            // CÁLCULOS
            
            // 1. Mano de obra
            const baseLaborCost = laborHours * hourlyRate;
            const benefitsCost = baseLaborCost * (benefits / 100);
            const extraHoursCost = baseLaborCost * (extraHours / 100) * 1.5; // Recargo 50% horas extra
            const totalLaborCost = baseLaborCost + benefitsCost + extraHoursCost;
            
            // 2. Materia prima (ya viene calculado)
            const materialCost = totalMaterialCost;
            
            // 3. Infraestructura
            const electricityCost = electricityHour * productionHours * electricityRate;
            const waterInfraCost = waterUsage * waterRate;
            const totalInfraCost = electricityCost + waterInfraCost + gasCost;
            
            // 4. Depreciación
            const depreciationPerHour = machineCost / (machineLife * hoursPerYear);
            const depreciationCost = depreciationPerHour * productionHours;
            const monthlyMaintenancePerLote = maintenance / 30; // Asumiendo 30 lotes por mes
            const totalDepreciationCost = depreciationCost + monthlyMaintenancePerLote;
            
            // 5. Costos indirectos
            const directCosts = totalLaborCost + materialCost + totalInfraCost;
            const supervisionCost = directCosts * (supervision / 100);
            const totalIndirectCost = supervisionCost + quality + cleaning;
            
            // 6. Total antes de administración
            const subtotal = totalLaborCost + materialCost + totalInfraCost + totalDepreciationCost + totalIndirectCost;
            const adminCost = subtotal * (admin / 100);
            const totalCostPerBatch = subtotal + adminCost;
            const costPerUnit = totalCostPerBatch / batchSize;
            
            // Actualizar resultados
            document.getElementById('laborTotal').innerHTML = `$${totalLaborCost.toFixed(2)} <span class="currency">MXN</span>`;
            document.getElementById('materialTotal').innerHTML = `$${materialCost.toFixed(2)} <span class="currency">MXN</span>`;
            document.getElementById('infraTotal').innerHTML = `$${totalInfraCost.toFixed(2)} <span class="currency">MXN</span>`;
            document.getElementById('depreciationTotal').innerHTML = `$${totalDepreciationCost.toFixed(2)} <span class="currency">MXN</span>`;
            document.getElementById('indirectTotal').innerHTML = `$${(totalIndirectCost + adminCost).toFixed(2)} <span class="currency">MXN</span>`;
            document.getElementById('totalCost').innerHTML = `$${totalCostPerBatch.toFixed(2)} <span class="currency">MXN</span>`;
            document.getElementById('unitCost').innerHTML = `$${costPerUnit.toFixed(4)} <span class="currency">MXN</span>`;
            
            // Precios sugeridos
            const price30 = costPerUnit * 1.3;
            const price50 = costPerUnit * 1.5;
            const price80 = costPerUnit * 1.8;
            
            document.getElementById('suggestedPrice30').textContent = `$${price30.toFixed(2)}`;
            document.getElementById('suggestedPrice50').textContent = `$${price50.toFixed(2)}`;
            document.getElementById('suggestedPrice80').textContent = `$${price80.toFixed(2)}`;
        }
        
        // Calcular automáticamente cuando se cambie cualquier input
        document.addEventListener('DOMContentLoaded', function() {
            const inputs = document.querySelectorAll('input[type="number"]');
            inputs.forEach(input => {
                input.addEventListener('input', calculateCosts);
            });
            
            // Cálculo inicial
            calculateCosts();
        });
    </script>
</body>
</html>
