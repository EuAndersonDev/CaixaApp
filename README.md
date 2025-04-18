# CaixaApp
---

```markdown
# 💰 AppCaixa

Aplicativo mobile feito com **React Native + Expo**, estilizado com **Tailwind CSS via NativeWind**, que consome uma API REST para controle de movimentações financeiras em um caixa.

---

## 📱 Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [NativeWind (Tailwind CSS para React Native)](https://www.nativewind.dev/)
- [Axios](https://axios-http.com/)
- [Node.js](https://nodejs.org/) + [Express](https://expressjs.com/) (no backend)

---

## 📂 Estrutura de Pastas

```
AppCaixa/
├── frontend/
│   ├── assets/             # Imagens e fontes
│   ├── components/         # Componentes reutilizáveis (ex: Card, Filtros, etc.)
│   ├── constants/          # Cores, textos e configs fixas
│   ├── hooks/              # Hooks personalizados (opcional)
│   ├── screens/            # Telas do app (Home, Detalhes, etc.)
│   ├── services/           # Comunicação com API (Axios)
│   ├── App.js              # Arquivo principal do app
│   ├── tailwind.config.js  # Configuração do Tailwind
│   └── babel.config.js     # Plugin do NativeWind
```

---

## 🚀 Como Rodar o Projeto

### Pré-requisitos

- Node.js e npm
- Expo CLI
- Dispositivo Android/iOS ou emulador
- Backend rodando localmente (porta 3000)

### 1. Instalar dependências

```bash
cd frontend
npm install
```

### 2. Rodar o app

```bash
npm start
# ou
npm run web       # para testar no navegador
```

Use o Expo Go no celular para escanear o QR Code e abrir o app.

---

## 🔗 Conexão com o Backend

A URL da API está definida em:

```js
// services/api.js
export const api = axios.create({
  baseURL: 'http://192.168.0.56:3000' // Substitua pelo IP da sua máquina na rede
});
```

---

## 🎨 Estilo com Tailwind (NativeWind)

Tailwind foi configurado usando `nativewind`. Você pode utilizar classes como:

```jsx
<View className="bg-zinc-900 p-4 rounded-xl">
  <Text className="text-white text-lg">Exemplo</Text>
</View>
```

---

## ✍️ Autor

**Anderson Reis**  
Desenvolvedor FullStack | GitHub: [@AndersonReis04](https://github.com/AndersonReis04)

---

## 📌 Objetivo do Projeto

Esse app foi criado como solução prática para gestão de caixa de pequenos negócios, com foco em:

- Registro de vendas por forma de pagamento
- Filtro por data (diário, semanal, mensal)
- Painel de resumo (em desenvolvimento)

---

## 📸 Prints (em breve)

> Adicione aqui imagens do app em uso para enriquecer seu portfólio

---

## 🧠 Aprendizados

- Organização de projeto mobile com componentes reutilizáveis
- Consumo de API REST com Axios
- Tailwind adaptado para mobile com NativeWind
- Deploy local e comunicação frontend-backend em rede local

---

## 📃 Licença

MIT © Anderson Reis
```

---

Se quiser, posso te ajudar a gerar os prints, criar badges automáticos ou até criar um gif do app funcionando. Quer isso também?
