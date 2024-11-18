
// Definir os pinos dos sensores
int turbidezPin = A0; 
int tdsPin = A1;

// Variáveis para armazenar os valores dos sensores
int valorTurbidez = 0;
int valorTDS = 0;

// Limites ajustados para determinar a potabilidade (valores mais realistas)
int limiteTurbidez = 100;  // Limite de turbidez (em NTU) para a água ser potável
int limiteTDS = 600;       // Limite de TDS (em ppm) para a água ser potável

void setup() {
  // Inicializar a comunicação serial para monitoramento
  Serial.begin(9600);
  Serial.println("Iniciando sistema de monitoramento da água...");
}

void loop() {
  // Ler os valores dos sensores
  valorTurbidez = analogRead(turbidezPin);  // Leitura do sensor de turbidez
  valorTDS = analogRead(tdsPin);            // Leitura do sensor de TDS
  
  // Convertendo o valor de 0-1023 para 0-100 NTU
  float turbidezEmNTU = map(valorTurbidez, 0, 1023, 0, 100);

  // Limitar a turbidez para 100 NTU no caso de leituras extremas
  if (turbidezEmNTU > 100) {
    turbidezEmNTU = 100;
  }

  // Ajuste na conversão de TDS (0 a 1023) para ppm (partes por milhão)
  float tdsEmPPM = map(valorTDS, 0, 1023, 0, 600);
  
  // Exibir os valores lidos no Monitor Serial
  Serial.print("Valor da turbidez (em NTU): ");
  Serial.println(turbidezEmNTU);
  
  Serial.print("Valor do TDS (em ppm): ");
  Serial.println(tdsEmPPM);

  // Aguardar 1 segundo antes de fazer a próxima leitura
  delay(10000);
}

