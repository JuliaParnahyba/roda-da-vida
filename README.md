# 🌱 Roda da Vida Interativa

Projeto de MVP para uma versão digital da tradicional **Roda da Vida** — ferramenta de autoconhecimento usada em processos de coaching, terapia e desenvolvimento pessoal.

## 🎯 Objetivo

Permitir que usuários avaliem o equilíbrio entre as principais áreas da vida por meio de uma interface amigável, com inputs manuais e um gráfico interativo. O MVP permite:

- Inserir notas de 0 a 10 para 12 áreas da vida
- Visualizar um gráfico dinâmico e responsivo
- Exportar o gráfico como PNG ou PDF

## 🧱 Stack do Projeto

- [Vue 3](https://vuejs.org/) (via Vite)
- [Tailwind CSS](https://tailwindcss.com/)
- [Chart.js](https://www.chartjs.org/)
- [html2canvas](https://html2canvas.hertzen.com/) (para exportação em imagem)
- [jsPDF](https://github.com/parallax/jsPDF) (opcional: exportar como PDF)

## 📦 Estrutura de Pastas (MVP)
```bash
src/
├── components/
│   ├── LifeAreaForm.vue      # Inputs das áreas
│   ├── LifeChart.vue         # Componente de gráfico
├── assets/
│   └── main.css              # Tailwind base
├── App.vue                   # Layout principal
├── main.js                   # Bootstrap do app
```

## 🗂️ Organização do Projeto

O projeto utiliza o GitHub Projects como kanban board de tarefas:
📍 **[Acesse aqui](https://github.com/SEU_USUARIO/roda-da-vida/projects)**


## 📅 Entrega do MVP

* Tempo estimado: **5 dias**
* Entregas organizadas em sprints
* Projeto versionado com branchs `main`, `dev`, `feature/*`

## ✨ Contribuição

Este projeto está sendo desenvolvido como um MVP pessoal, mas poderá futuramente ser aberto para contribuições externas.


## 🧑‍💻 Licença

Em desenvolvimento — licença será definida ao final da fase MVP.