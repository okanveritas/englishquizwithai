# CEFR İngilizce Seviye Tespit Sınavı

## Recent Updates (July 16, 2025)

✅ **Project Simplification**: Tek odak - CEFR seviye testi sayfası
✅ **File Structure Cleanup**: Gereksiz HTML/JS/CSS dosyaları kaldırıldı
✅ **Main Site Identity**: standalone-quiz.html → index.html olarak değiştirildi  
✅ **README Overhaul**: CEFR test odaklı kapsamlı dokümantasyon
✅ **Repository Focus**: Sadece seviye testi için optimize edildi
✅ **GitHub Pages Ready**: Tek sayfa odaklı deployment hazır

## Overview

Professional CEFR English proficiency assessment test using pure HTML, CSS, and JavaScript. Features 60-question comprehensive evaluation covering Grammar, Vocabulary, Reading, and Cloze test categories. Modern cinema-style navigation with color-coded progress tracking, detailed performance analysis, and surprise level determination based on hidden CEFR criteria. Perfect responsive design with light/dark theme support and GitHub Pages deployment capability.

## User Preferences

Preferred communication style: Simple, everyday language in Turkish.
Technology preference: HTML, CSS, and JavaScript only - no frameworks for GitHub Pages compatibility.
Design preference: Modern, clean interface with professional quiz preparation focus.
Key features: AI-powered platform, customizable prompt generator with area selection (grammar, vocabulary) and question count, flashcard system for vocabulary study, ChatGPT integration via copy-paste.

## System Architecture

The application follows a simple client-side architecture using vanilla web technologies:

### Frontend Architecture
- **Languages**: HTML5, CSS3, and JavaScript ES6+
- **Styling**: Custom CSS with modern techniques (Flexbox, Grid, CSS Variables)
- **State Management**: Plain JavaScript with DOM manipulation
- **Storage**: Local variables and browser localStorage
- **UI Components**: Custom HTML elements with CSS styling
- **Responsive Design**: Mobile-first approach with CSS media queries

### No Backend Required
- **Data Storage**: Client-side only with JSON input validation
- **Processing**: All quiz logic handled in browser JavaScript
- **Export**: Client-side file download functionality
- **No Server**: Static files served directly

## Key Components

### Core Files
- **quiz-app.html**: Main HTML structure with semantic markup
- **quiz-app.css**: Modern CSS with CSS variables for theming
- **quiz-app.js**: Complete JavaScript application logic

### Modern UI Features
- **Enhanced Head Section**: Complete SEO optimization with Open Graph, Twitter cards, favicon (AI Quiz-focused)
- **Navigation System**: Quiz and Flashcard sections with clean header navigation
- **Customizable Prompt Generator**: AI-powered topics with selectable question counts and difficulty levels
- **Dynamic Prompt Templates**: 8 quiz categories (Karma, Reading, Grammar, Vocabulary, Sentence, Phrasal, Idioms, Academic)
- **Flashcard System**: Interactive vocabulary cards with flip animation, progress tracking, and keyboard navigation
- **Copy-Paste Integration**: Direct clipboard functionality for ChatGPT prompt sharing and vocabulary input
- **Reading Passage Auto-Detection**: Automatic detection from quiz type and question patterns
- **AI-Powered Features**: Specialized for English quiz preparation with Turkish interface
- **Enhanced Coaching System**: Detailed AI-specific performance analysis
- **Smart Timer**: 30-second countdown that only resets on question change
- **Responsive Design**: Mobile-first approach with touch-friendly interactions
- **Theme System**: Light/dark mode with localStorage persistence

## Key Components

### Data Storage
- **Primary**: In-memory storage implementation (`MemStorage` class) for development
- **Configured**: PostgreSQL with Drizzle ORM for production (schema defined but not actively used)
- **Schema**: Well-defined database schema for quizzes and quiz sessions

### Frontend Components
- **UploadSection**: Handles JSON quiz data validation and upload
- **QuizSection**: Interactive quiz interface with progress tracking
- **ResultsSection**: Detailed results display with wrong answer analysis
- **UI Components**: Comprehensive shadcn/ui component library

### Backend Services
- **Storage Interface**: Abstract storage interface allowing easy switching between implementations
- **Quiz Validation**: Comprehensive JSON schema validation using Zod
- **API Routes**: Clean RESTful endpoints for quiz operations

## Data Flow

1. **Quiz Creation**:
   - User uploads JSON quiz data through the upload interface
   - Backend validates the JSON structure and question format
   - Quiz is stored in memory (or database in production)
   - Frontend receives quiz ID and proceeds to quiz interface

2. **Quiz Taking**:
   - Frontend fetches quiz data and renders interactive questions
   - User answers are tracked locally during the quiz
   - Progress is shown with visual indicators

3. **Quiz Submission**:
   - All answers are submitted as a batch to the backend
   - Backend calculates score and generates detailed results
   - Results include correct/incorrect answers and explanations

## External Dependencies

### Frontend Dependencies
- **UI Framework**: React with extensive Radix UI primitives
- **Styling**: Tailwind CSS with CSS variables for theming
- **State Management**: TanStack Query for API state
- **Form Validation**: Zod for runtime type checking
- **Icons**: Lucide React for consistent iconography

### Backend Dependencies
- **Database**: Neon serverless PostgreSQL (configured)
- **ORM**: Drizzle for type-safe database operations
- **Validation**: Zod for request/response validation
- **Session Management**: Connect-pg-simple for PostgreSQL sessions

### Development Dependencies
- **Build Tools**: Vite with React plugin
- **Development**: TSX for TypeScript execution
- **Database Tools**: Drizzle Kit for migrations
- **Replit Integration**: Custom plugins for Replit environment

## Deployment Strategy

### Development
- **Frontend**: Vite dev server with HMR
- **Backend**: Express server with TSX for TypeScript execution
- **Database**: In-memory storage for rapid development
- **Build**: Separate build processes for client and server

### Production
- **Frontend**: Static build served by Express
- **Backend**: Compiled JavaScript bundle
- **Database**: PostgreSQL with proper connection pooling
- **Environment**: Environment variables for database configuration

### Architecture Decisions

1. **Pure HTML/CSS/JavaScript**: No frameworks for GitHub Pages compatibility and maximum simplicity.

2. **YDS-Focused Design**: Specialized specifically for YDS exam preparation rather than general English testing.

3. **Modular JavaScript**: Clean separation of concerns with dedicated functions for navigation, prompt generation, and flashcard functionality.

4. **Client-Side Processing**: All functionality handled in browser without backend dependencies for static hosting.

5. **Progressive Enhancement**: Core features work with fallbacks for older browser compatibility.

### Recent Changes (Latest Session)

#### Phase 1: Core Platform Development
- ✅ **Platform Rebrand**: Changed from general English quiz platform to AI-focused preparation platform
- ✅ **Navigation System**: Added header navigation with Quiz and Flashcard sections
- ✅ **Prompt Generator**: Implemented customizable AI prompt generator with 8 study areas, question counts, and difficulty levels
- ✅ **Flashcard System**: Complete vocabulary flashcard functionality with flip animations, progress tracking, keyboard navigation
- ✅ **AI-Specific Content**: Replaced general prompts with AI-focused templates and examples
- ✅ **Quiz Reinforcement**: "Quiz Yap" feature for flashcard vocabulary double-learning

#### Phase 2: Production-Ready Enhancement
- ✅ **Hero Landing Page**: Professional homepage with feature showcase and call-to-action buttons
- ✅ **About Page**: Complete founder profiles (Okan Yaldız ♂, Eylül Han ♀), mission, vision
- ✅ **Responsive Design**: Full mobile/tablet/desktop optimization with CSS Grid and Flexbox
- ✅ **Enhanced Navigation**: 4-section navigation (Ana Sayfa, Quiz, Flashcard, Hakkımızda)
- ✅ **CSS Architecture**: Modern CSS with variables, gradients, and responsive breakpoints
- ✅ **GitHub Ready**: Complete documentation (README, LICENSE, CONTRIBUTING, .gitignore)
- ✅ **Timer System**: Fixed timer issues for flashcard-generated quizzes
- ✅ **Navigation Fix**: Resolved CSS conflicts between inline styles and class-based navigation

#### Phase 3: Final Polish & Deployment (Current Session)
- ✅ **Secondary Button Fix**: Resolved "Vocabulary Çalış" button visibility in light theme
- ✅ **Homepage Enhancement**: Added detailed descriptions to stats cards (Sınırsız Quiz, 100% Ücretsiz, 24/7 Erişim, AI Destekli)
- ✅ **Contact Integration**: Added okanyaldiz@icloud.com and linkedin.com/in/okanyaldiz to founder profile
- ✅ **Professional Styling**: Enhanced infinity symbol typography, gradient animations, shimmer effects
- ✅ **Content Optimization**: Complete site content refinement for AI quiz focus
- ✅ **Theme Consistency**: Perfect light/dark mode compatibility across all sections
- ✅ **Contact Section**: Enhanced contact & support section with professional styling
- ✅ **Ready for Deployment**: Complete, polished, production-ready AI quiz preparation platform

#### Phase 4: Final Branding Update (Previous Session)
- ✅ **Complete Rebrand**: Changed all "YDS Hazırlık Platformu" references to "AI Destekli Quiz"
- ✅ **Prompt Updates**: Removed all YDS-specific terminology from quiz prompts and examples
- ✅ **Flashcard Rebranding**: Updated "YDS Vocabulary" to "İnteraktif Flashcard'lar"
- ✅ **Interface Refinement**: Changed "vocabulary çalış" to "flashcard" throughout interface
- ✅ **Content Generalization**: Made all content more marketing-friendly and general quiz-focused
- ✅ **Documentation Update**: Updated replit.md to reflect new AI-focused branding

#### Phase 5: CEFR Level Test Styling Resolution (Previous Session)
- ✅ **Test Start Button Fix**: Resolved visibility issues for "Seviye Tespit Sınavını Başlat" button with !important CSS rules
- ✅ **Navigation Buttons**: Confirmed "önceki/sonraki/testi bitir" buttons working properly
- ✅ **Question Content**: Verified grammar questions and fill-in-the-blank sections display correctly
- ✅ **Option Button Styling**: Fixed critical issue with test option buttons (şıklar) not displaying properly
- ✅ **CSS Architecture**: Implemented comprehensive inline styling with !important rules for option buttons
- ✅ **Global Override**: Added forced styling for all test option buttons across different question types
- ✅ **User Confirmation**: Successfully resolved all styling issues in placement test section

#### Phase 6: Final Site Consistency & GitHub Deployment (Current Session - July 16, 2025)
- ✅ **Question Navigator Redesign**: Converted CSS Grid to Flexbox for proper 1,2,3... sequencing
- ✅ **Cinema Seat Style**: Implemented round buttons (28px) with proper horizontal layout
- ✅ **Color-Coded Navigation**: Current question (orange), answered (green), unanswered (gray)
- ✅ **Site-Wide Footer Integration**: Added consistent footer across all pages with contact info
- ✅ **Light Theme Contrast Fix**: Resolved purple gradient readability issues in light mode
- ✅ **README Documentation**: Updated all content to reflect AI-focused branding
- ✅ **Landing Page Creation**: Professional index.html with hero section and feature showcase
- ✅ **Brand Consistency**: Unified "AI Destekli Quiz Platformu" naming across all files
- ✅ **GitHub Ready**: Complete platform ready for deployment with proper file structure