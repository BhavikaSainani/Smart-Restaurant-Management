# 🍽️ BiteWise - Smart Restaurant Management

![BiteWise Banner](https://img.shields.io/badge/BiteWise-Smart%20Restaurant%20System-blue?style=for-the-badge) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)

Welcome to **BiteWise**, a modern, comprehensive, and scalable Smart Restaurant Management platform designed to streamline operations from order taking to kitchen prep and delivery.

## 🌟 Key Features

BiteWise divides the restaurant workflow into dedicated interfaces for smooth execution:

- **👨‍🍳 Chef Interface**: Real-time order monitoring with item-level status updates (Pending → Preparing → Ready).
- **🤵 Waiter Interface**: Seamless order management ensuring prompt delivery to tables when items change to "Ready".
- **👤 Customer Interface**: An intuitive, contactless digital menu and ordering experience.
- **🛡️ Admin Dashboard**: Overview of restaurant performance, inventory tracking, menu modifications, and user management.

## 💡 How It Works

BiteWise boasts **Status Consistency Tracking**, meaning all interfaces share a single source of truth. Orders are tracked strictly using an **item-level status system**:
`Pending` ➔ `Preparing` ➔ `Ready` ➔ `Served`

This eliminates confusion and creates a true real-time transparent workflow across the entire restaurant.

## 🛠️ Technology Stack

- **Frontend**: React.js with Vite
- **Styling**: Tailwind CSS & shadcn/ui for sleek, modern, and accessible UI components
- **Language**: TypeScript for robust typing and maintainability

## 🚀 Getting Started

Follow these steps to set up the local development environment:

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn installed

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/BhavikaSainani/Smart-Restaurant-Management.git
   cd Smart-Restaurant-Management
   ```

2. **Install the dependencies:**
   ```sh
   npm install
   ```

3. **Start the development server:**
   ```sh
   npm run dev
   ```

## 📱 Running Locally

After running the development server, your application will be available at [http://localhost:5173](http://localhost:5173). 
Open this address in your browser to explore the different dashboards.

---
_BiteWise - Enhancing the modern dining experience._
