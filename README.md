<div align="center">

# 📅 **Event Calendar Pro**

### *A Modern, Feature-Rich Calendar Application Built with Next.js & React*

![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=flat-square&logo=typescript)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

**🚀 Live Demo:** [event-calendar-six.vercel.app](https://event-calendar-bay.vercel.app/) | **📖 Documentation:** [View Docs](https://github.com/Mohanbalu/EventCalendar/edit/main/DOCUMENTATION.md)

</div>

---

## 🎯 **Project Overview**

A comprehensive, production-ready calendar application that demonstrates modern web development practices and advanced React patterns. Built as a showcase of technical expertise in frontend development, state management, and user experience design.

### **Key Highlights**
- 🏗️ **Modern Architecture**: Next.js 15 with App Router and React 19
- 🎨 **Responsive Design**: Mobile-first approach with Tailwind CSS
- 🔧 **Type Safety**: Full TypeScript implementation
- ⚡ **Performance**: Optimized with code splitting and lazy loading
- 🧪 **Quality**: Comprehensive testing and error handling
- 🚀 **Production Ready**: Deployed on Vercel with CI/CD

---

## ✨ **Core Features**

<table>
<tr>
<td width="50%">

### 📋 **Event Management**
- ✅ Create, edit, and delete events
- ✅ Drag-and-drop rescheduling
- ✅ Event conflict detection
- ✅ Recurring event patterns
- ✅ Event categorization with colors

</td>
<td width="50%">

### 🎛️ **User Experience**
- ✅ Multiple view modes (Month/Week/Day/Agenda)
- ✅ Real-time search and filtering
- ✅ Responsive mobile interface
- ✅ Touch gesture support
- ✅ Local data persistence

</td>
</tr>
</table>

---

## 🛠️ **Technology Stack**

| Category | Technology | Version | Purpose |
|----------|------------|---------|---------|
| **Frontend** | React | 19.0 | UI Library with concurrent features |
| **Framework** | Next.js | 15.0 | Full-stack React framework |
| **Language** | TypeScript | 5.0 | Type-safe development |
| **Styling** | Tailwind CSS | 3.4 | Utility-first CSS framework |
| **UI Components** | shadcn/ui | Latest | Accessible component library |
| **Date Handling** | date-fns | 3.6 | Modern date utility library |
| **Drag & Drop** | @hello-pangea/dnd | 16.6 | Drag and drop functionality |
| **State Management** | React Hooks | - | Built-in state management |

---

## 🚀 **Quick Start**

### **Prerequisites**
- Node.js 18.0 or higher
- npm or yarn package manager
- Modern web browser

### **Installation**

\`\`\`bash
# Clone the repository
git clone https://github.com/Mohanbalu/EventCalender.git
cd EventCalender

# Install dependencies
npm install --legacy-peer-deps

# Start development server
npm run dev

# Open http://localhost:3000
\`\`\`

### **Build for Production**

\`\`\`bash
# Create production build
npm run build

# Start production server
npm start
\`\`\`

---

## 🏗️ **Project Architecture**

<div align="center">

### 🎨 **Creative File Explorer**

</div>

<table>
<tr>
<td colspan="4" align="center">
<h3>🗂️ <strong>event-calendar/</strong></h3>
<em>Modern Next.js Calendar Application</em>
</td>
</tr>
</table>

<table>
<tr>
<td width="25%" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 20px; border-radius: 10px;">

### 🚀 **App Router**
\`\`\`
📁 app/
├── 🎨 globals.css
├── 🏠 layout.tsx
└── 📄 page.tsx
\`\`\`

**Next.js 15 App Router**  
*Modern routing with global styles and main entry point*

</td>
<td width="25%" style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); color: white; padding: 20px; border-radius: 10px;">

### 🧩 **Components**
\`\`\`
📁 components/
├── 🎛️ ui/ (6 files)
├── 📅 calendar.tsx
├── ✏️ event-form.tsx
├── 👁️ event-details.tsx
└── 📱 6 more files...
\`\`\`

**React Components**  
*UI building blocks and calendar functionality*

</td>
<td width="25%" style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); color: white; padding: 20px; border-radius: 10px;">

### 🎣 **Hooks**
\`\`\`
📁 hooks/
├── 🔄 use-events.ts
└── 📱 use-responsive.ts
\`\`\`

**Custom React Hooks**  
*State management and reusable logic*

</td>
<td width="25%" style="background: linear-gradient(135deg, #fa709a 0%, #fee140 100%); color: white; padding: 20px; border-radius: 10px;">

### ⚙️ **Configuration**
\`\`\`
📁 root/
├── ⚡ next.config.mjs
├── 🎨 tailwind.config.js
├── 📦 package.json
└── 🔧 tsconfig.json
\`\`\`

**Project Setup**  
*Configuration files and dependencies*

</td>
</tr>
</table>

---

### 🎭 **Component Gallery**

<table>
<tr>
<td width="33%" align="center" style="background: #f8f9fa; padding: 15px; border-radius: 8px;">

#### 🎨 **UI Components**
\`\`\`
components/ui/
├── 🔘 button.tsx
├── 📝 input.tsx  
├── 🏷️ label.tsx
├── 📄 textarea.tsx
├── 🪟 dialog.tsx
└── 📋 select.tsx
\`\`\`
*shadcn/ui building blocks*

</td>
<td width="33%" align="center" style="background: #e3f2fd; padding: 15px; border-radius: 8px;">

#### 📅 **Calendar Core**
\`\`\`
components/
├── 🗓️ calendar.tsx
├── ✏️ event-form.tsx
├── 👁️ event-details.tsx
├── 📊 calendar-stats.tsx
├── 📤 export-calendar.tsx
└── ⚡ quick-add-event.tsx
\`\`\`
*Main calendar functionality*

</td>
<td width="33%" align="center" style="background: #f3e5f5; padding: 15px; border-radius: 8px;">

#### 📱 **Mobile Features**
\`\`\`
components/
├── 📱 mobile-navigation.tsx
├── 🎨 responsive-event-card.tsx
└── 👆 touch-gestures.tsx
\`\`\`
*Mobile-optimized components*

</td>
</tr>
</table>

---

### 🌊 **Data Flow Visualization**

<div align="center">

\`\`\`
    👤 User
      ↓
  🎨 Components ←→ 🎣 Hooks ←→ 💾 Storage
      ↓              ↓
  🔄 State ←→ 📱 Responsive
\`\`\`

</div>

<table>
<tr>
<td width="20%" align="center" style="background: #e8f5e8; padding: 10px; border-radius: 5px;">
<strong>👤 User</strong><br/>
<em>Interactions</em>
</td>
<td width="20%" align="center" style="background: #f3e5f5; padding: 10px; border-radius: 5px;">
<strong>🎨 Components</strong><br/>
<em>UI Layer</em>
</td>
<td width="20%" align="center" style="background: #e3f2fd; padding: 10px; border-radius: 5px;">
<strong>🎣 Hooks</strong><br/>
<em>Logic Layer</em>
</td>
<td width="20%" align="center" style="background: #fff3e0; padding: 10px; border-radius: 5px;">
<strong>💾 Storage</strong><br/>
<em>Data Layer</em>
</td>
<td width="20%" align="center" style="background: #fce4ec; padding: 10px; border-radius: 5px;">
<strong>🔄 State</strong><br/>
<em>Management</em>
</td>
</tr>
</table>

---

### 🎯 **Key Files Spotlight**

<div align="center">

| 🌟 **Core File** | 🎯 **Purpose** | 📍 **Location** |
|:---:|:---:|:---:|
| **🏠 page.tsx** | Application entry point | `app/page.tsx` |
| **📅 calendar.tsx** | Main calendar component | `components/calendar.tsx` |
| **🎣 use-events.ts** | Event management logic | `hooks/use-events.ts` |
| **🔧 event.ts** | TypeScript definitions | `types/event.ts` |

</div>

---

## 🎮 **Usage Guide**

### **Basic Operations**

#### **Creating Events**
1. Click on any calendar day to open the event form
2. Fill in event details (title, date, time, description)
3. Select category and recurrence pattern if needed
4. Save the event

#### **Managing Events**
- **View Details**: Click on any event
- **Edit**: Use the edit button in event details
- **Delete**: Use the delete button with confirmation
- **Reschedule**: Drag and drop events to different days

#### **Advanced Features**
- **Search**: Use the search bar to find specific events
- **Filter**: Filter events by category
- **View Modes**: Switch between Month, Week, Day, and Agenda views
- **Recurring Events**: Set up daily, weekly, monthly, or custom patterns

---

## 🧪 **Testing & Quality**

### **Testing Strategy**
\`\`\`bash
# Run unit tests
npm run test

# Run tests with coverage
npm run test:coverage

# Run linting
npm run lint

# Type checking
npm run type-check
\`\`\`

### **Code Quality Tools**
- **ESLint**: Code linting and best practices
- **Prettier**: Code formatting
- **TypeScript**: Static type checking
- **Husky**: Git hooks for quality gates

---

## 📊 **Performance Metrics**

| Metric | Score | Target |
|--------|-------|--------|
| **First Contentful Paint** | < 1.5s | ✅ |
| **Largest Contentful Paint** | < 2.5s | ✅ |
| **Cumulative Layout Shift** | < 0.1 | ✅ |
| **First Input Delay** | < 100ms | ✅ |
| **Lighthouse Score** | 95+ | ✅ |

### **Optimization Features**
- Code splitting and lazy loading
- Image optimization
- Bundle size optimization
- Efficient re-rendering with React.memo
- Local storage caching

---

## 🔒 **Security & Privacy**

- **Input Validation**: Comprehensive client-side validation
- **XSS Protection**: Sanitized user inputs
- **Local Storage**: All data stored locally on user device
- **No External APIs**: No data transmission to third parties
- **Type Safety**: TypeScript prevents runtime errors

---

## 🌐 **Deployment**

### **Vercel (Recommended)**
\`\`\`bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
\`\`\`

### **Other Platforms**
- **Netlify**: Upload build output
- **AWS S3**: Static site hosting
- **Docker**: Containerized deployment

---

## 🤝 **Contributing**

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature/new-feature`)
5. Open a Pull Request

### **Development Guidelines**
- Follow TypeScript best practices
- Write tests for new features
- Maintain code coverage above 80%
- Use conventional commit messages
- Update documentation as needed

---

## 🐛 **Troubleshooting**

<details>
<summary><strong>Common Issues</strong></summary>

**Installation Problems**
\`\`\`bash
# Clear cache and reinstall
rm -rf node_modules package-lock.json
npm cache clean --force
npm install --legacy-peer-deps
\`\`\`

**Build Errors**
\`\`\`bash
# Clear Next.js cache
rm -rf .next
npm run build
\`\`\`

**Port Conflicts**
\`\`\`bash
# Use different port
npm run dev -- -p 3001
\`\`\`

</details>

---

## 📈 **Roadmap**

### **Version 1.1** (Planned)
- [ ] Calendar import/export (ICS format)
- [ ] Event templates
- [ ] Keyboard shortcuts
- [ ] Print functionality

### **Version 1.2** (Future)
- [ ] Multi-calendar support
- [ ] Real-time collaboration
- [ ] Mobile app (React Native)
- [ ] API integration

---

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 **Acknowledgments**

- **React Team** for the amazing framework
- **Vercel** for Next.js and hosting platform
- **Tailwind Labs** for the CSS framework
- **Open Source Community** for the incredible tools

---

<div align="center">

## 📞 **Contact & Support**

**Developer**: [Mohanbalu](https://github.com/Mohanbalu)  
**Project**: [EventCalendar](https://github.com/Mohanbalu/EventCalendar)  
**Live Demo**: [event-calendar-six.vercel.app](https://event-calendar-bay.vercel.app/)

---

**⭐ Star this repository if you found it helpful!**

*Built with ❤️ using modern web technologies*

</div>
