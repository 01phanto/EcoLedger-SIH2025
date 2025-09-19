# 🌿 EcoLedger - Blockchain Carbon Credit Marketplace

> **Smart India Hackathon 2025 Prototype**  
> A transparent blockchain-based platform for tracking and trading carbon credits generated through mangrove plantation projects.

![EcoLedger Banner](./src/assets/hero-mangroves.jpg)

## 🎯 Problem Statement

Climate change mitigation requires innovative solutions for carbon offset tracking. Traditional carbon credit systems lack transparency, verification, and accessibility for small-scale environmental projects. EcoLedger addresses these challenges by creating a decentralized marketplace for carbon credits.

## 💡 Solution Overview

EcoLedger is a comprehensive platform that:
- **Tracks** mangrove plantation projects in real-time
- **Verifies** environmental impact through admin oversight
- **Generates** carbon credits based on verified plantations
- **Facilitates** transparent trading of carbon credits
- **Records** all transactions on blockchain for immutability

## 🚀 Key Features

### 🌱 For NGOs & Environmental Organizations
- Submit plantation data with GPS coordinates
- Upload verification images
- Track credit generation from projects
- Monitor approval status in real-time

### 🛒 For Carbon Credit Buyers
- Browse verified carbon credits marketplace
- Purchase credits with transparent pricing
- View detailed project information
- Track purchase history and impact

### 🔐 For Administrators
- Review and verify plantation submissions
- Approve/reject projects with detailed oversight
- Monitor platform-wide statistics
- Ensure quality control and compliance

### 📊 Blockchain Transparency
- Immutable transaction records
- Public ledger for all credit transfers
- Cryptographic verification of all activities
- Complete audit trail for regulatory compliance

## 🛠️ Technology Stack

### Frontend
- **React 18** with TypeScript for type safety
- **Vite** for fast development and optimized builds
- **Tailwind CSS** for modern, responsive design
- **Shadcn/UI** for consistent component library
- **React Router** for seamless navigation

### State Management & Data
- **React Context API** for global state
- **React Query** for efficient data fetching
- **React Hook Form** for form management

### Development Tools
- **ESLint & TypeScript** for code quality
- **PostCSS & Autoprefixer** for CSS optimization
- **Lucide React** for consistent iconography

## 📱 User Roles & Workflows

### NGO Workflow
1. Register and login to NGO dashboard
2. Submit plantation project details
3. Upload GPS coordinates and images
4. Wait for admin verification
5. Receive carbon credits upon approval
6. Track earnings and project impact

### Buyer Workflow
1. Access buyer dashboard
2. Browse available carbon credits
3. View project details and verification
4. Purchase credits with transparent pricing
5. Track portfolio and environmental impact

### Admin Workflow
1. Monitor pending project submissions
2. Review plantation evidence and data
3. Verify GPS coordinates and images
4. Approve or reject submissions
5. Oversee platform integrity

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Shadcn/UI component library
│   └── ErrorBoundary   # Error handling
├── contexts/           # React Context providers
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
├── pages/              # Main application pages
│   ├── Index.tsx       # Landing page
│   ├── NGODashboard.tsx
│   ├── BuyerDashboard.tsx
│   ├── AdminPanel.tsx
│   └── BlockchainLedger.tsx
└── assets/             # Static assets
```

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ installed
- npm or yarn package manager

### Installation & Setup

```bash
# Clone the repository
git clone <your-repo-url>
cd EcoLedger_Prototype

# Install dependencies
npm install

# Start development server
npm run dev

# Open browser to http://localhost:8080
```

### Build for Production

```bash
# Create optimized production build
npm run build

# Preview production build
npm run preview
```

## 🎮 Demo Instructions

### Test User Roles

1. **NGO User**: Enter any name/email → Select "NGO" → Submit plantation data
2. **Buyer User**: Enter any name/email → Select "Buyer" → Browse and purchase credits
3. **Admin User**: Enter any name/email → Select "Admin" → Review and approve submissions

### Sample Data Flow
1. Login as NGO → Submit a plantation project
2. Login as Admin → Verify and approve the project
3. Login as Buyer → Purchase the generated carbon credits
4. View Blockchain Ledger → See complete transaction history

## 🌟 Innovation Highlights

### Environmental Impact
- **Direct CO₂ Reduction**: Each mangrove tree absorbs 35kg CO₂ annually
- **Biodiversity Protection**: Supports marine ecosystem restoration
- **Community Engagement**: Empowers local environmental initiatives

### Technology Innovation
- **Blockchain Integration**: Ensures transparency and prevents double-spending
- **Real-time Verification**: GPS-based project validation
- **Responsive Design**: Accessible across all devices
- **Scalable Architecture**: Built for growth and expansion

### Social Impact
- **Accessibility**: Simple interface for non-technical users
- **Transparency**: Complete visibility into credit lifecycle
- **Fair Pricing**: Market-driven carbon credit valuation
- **Global Reach**: Platform supports international projects

## 📊 Platform Statistics (Demo Data)

- **Projects Submitted**: Real-time tracking
- **Credits Generated**: Based on verified plantations
- **Transactions Completed**: Transparent blockchain records
- **Environmental Impact**: CO₂ offset calculations

## 🔮 Future Roadmap

### Phase 1 (Current)
- ✅ Core marketplace functionality
- ✅ Multi-role user system
- ✅ Basic blockchain simulation

### Phase 2 (Planned)
- [ ] Real blockchain integration (Ethereum/Polygon)
- [ ] IoT sensor integration for automatic monitoring
- [ ] Mobile application development
- [ ] Payment gateway integration

### Phase 3 (Vision)
- [ ] AI-powered project verification
- [ ] Satellite imagery integration
- [ ] Global expansion and partnerships
- [ ] Regulatory compliance framework

## 👥 Team Information

**Hackathon Team**: [Your Team Name]  
**Institution**: [Your College/Organization]  
**SIH Problem Statement**: [PS Number and Title]

## 📄 License

This project is developed for Smart India Hackathon 2025.

## 🤝 Contributing

This is a hackathon prototype. For contributions or questions, please contact the development team.

---

**Built with ❤️ for a sustainable future** 🌍
