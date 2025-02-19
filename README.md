# 🌍 GeoRegistro - Sistema de Circunscrição Imobiliária de São Luís/MA  

O **GeoRegistro** é um sistema web que auxilia os usuários a identificarem a qual circunscrição imobiliária de **São Luís/MA** pertence um imóvel, a partir do endereço inserido.  

🔗 **Acesse o sistema online:** [GeoRegistro](https://1fms.github.io/ZonasRI/)  

## 🛠️ Tecnologias Utilizadas  

- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Mapas e Geolocalização:** Leaflet.js, Turf.js, OpenStreetMap (Nominatim)  
 
## 🚀 Funcionalidades  

✅ **Consulta de circunscrição:** O usuário insere o endereço e o sistema verifica em qual zona imobiliária o imóvel está localizado.  
✅ **Mapa interativo:** Utiliza **Leaflet.js** para exibir e manipular os mapas.  
✅ **Geolocalização automática:** Conversão do endereço para coordenadas usando **Nominatim (OpenStreetMap)**.  
✅ **Análise de polígonos:** Com **Turf.js**, verifica se o ponto está dentro de uma zona definida no **GeoJSON**.  

## 📦 Instalação e Configuração  

1. **Clone o repositório:**  
   ```bash
   git clone https://github.com/1fms/ZonasRI.git
   ```

2. **Hospede o projeto:**  
   - Basta abrir o `index.html` no navegador.  

3. **Adicione o arquivo GeoJSON:**  
   - Adicione o arquivo `zonas.geojson` na pasta do projeto.  

4. **Acesse o sistema no navegador:**  
   ```
   http://localhost/seuprojeto
   ```
