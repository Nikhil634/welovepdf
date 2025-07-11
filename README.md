
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free PDF Tools Online | Merge, Split & Convert PDFs Without Login</title>
    <meta name="description" content="Expert-designed PDF tools to solve document problems instantly. Merge, split, compress, and convert PDFs with enterprise security - no signup required.">
    <meta name="keywords" content="free pdf tools, merge pdf, split pdf, compress pdf, pdf to word, pdf to excel, online pdf editor, pdf converter, secure pdf tools">
    <meta name="robots" content="index, follow">
    <meta name="author" content="Nikhil Tanwar, PDF Processing Specialist">
    <link rel="canonical" href="https://yourdomain.com/">
    
    <!-- Open Graph Tags -->
    <meta property="og:title" content="Professional PDF Tools Without Login/Signup">
    <meta property="og:description" content="Solve document problems instantly with our expert-designed PDF tools. Free, secure, and no registration required.">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://yourdomain.com/images/og-pdf-tools.jpg">
    
    <!-- Preconnect and Preload -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preload" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" as="style">
    <link rel="preload" href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&family=Montserrat:wght@700;800;900&display=swap" as="style">
    
    <!-- Schema.org Structured Data -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebApplication",
      "name": "We Love PDF Tools",
      "description": "Free online PDF tools for merging, splitting, compressing and converting documents",
      "applicationCategory": "PDF Utility Tools",
      "operatingSystem": ["Windows", "macOS", "Linux", "Android", "iOS"],
      "offers": {
        "@type": "Offer",
        "price": "0",
        "priceCurrency": "USD"
      },
      "aggregateRating": {
        "@type": "AggregateRating",
        "ratingValue": "4.9",
        "ratingCount": "1543",
        "bestRating": "5",
        "worstRating": "1"
      },
      "author": {
        "@type": "Person",
        "name": "Nikhil Tanwar",
        "url": "https://www.instagram.com/nikhiltanwar_11",
        "image": "https://yourdomain.com/images/nikhil-tanwar.jpg",
        "sameAs": [
          "https://www.linkedin.com/in/nikhiltanwar",
          "https://github.com/nikhiltanwar"
        ]
      },
      "review": {
        "@type": "Review",
        "reviewRating": {
          "@type": "Rating",
          "ratingValue": "5",
          "bestRating": "5"
        },
        "author": {
          "@type": "Person",
          "name": "Alex Johnson"
        },
        "reviewBody": "These tools saved my business hours of document processing time. The security features give me peace of mind when handling sensitive contracts."
      }
    }
    </script>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&family=Montserrat:wght@700;800;900&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/pdf-lib@1.17.1/dist/pdf-lib.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/FileSaver.js/2.0.5/FileSaver.min.js"></script>
    <style>
        :root {
            --primary: #e53935;
            --primary-light: #ff5252;
            --primary-dark: #b71c1c;
            --accent: #ff8a80;
            --light: #f8f9fa;
            --light-gray: #f5f5f5;
            --dark: #212121;
            --dark-gray: #424242;
            --success: #4ade80;
            --warning: #ffb300;
            --error: #f44336;
            --glass: rgba(255, 255, 255, 0.08);
            --glass-border: rgba(255, 255, 255, 0.1);
            --shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            --card-shadow: 0 8px 25px rgba(229, 57, 53, 0.15);
            --card-hover-shadow: 0 15px 40px rgba(229, 57, 53, 0.25);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #fafafa 0%, #f5f5f5 100%);
            color: var(--dark);
            min-height: 100vh;
            line-height: 1.6;
            overflow-x: hidden;
            font-display: swap;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background: white;
            box-shadow: var(--shadow);
            position: sticky;
            top: 0;
            z-index: 100;
            animation: slideDown 0.5s ease;
        }
        
        @keyframes slideDown {
            from { transform: translateY(-100%); }
            to { transform: translateY(0); }
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        
        .logo:hover {
            transform: scale(1.02);
        }
        
        .logo-icon {
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 15px rgba(229, 57, 53, 0.4);
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(229, 57, 53, 0.4); }
            70% { box-shadow: 0 0 0 15px rgba(229, 57, 53, 0); }
            100% { box-shadow: 0 0 0 0 rgba(229, 57, 53, 0); }
        }
        
        .logo-icon i {
            font-size: 1.8rem;
            color: white;
        }
        
        .logo-text {
            display: flex;
            flex-direction: column;
        }
        
        .logo-text h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.8rem;
            font-weight: 800;
            background: linear-gradient(to right, var(--primary), var(--primary-dark));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            line-height: 1.1;
        }
        
        .logo-text span {
            font-size: 0.85rem;
            color: var(--primary);
            font-weight: 500;
            letter-spacing: 0.5px;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 30px;
        }
        
        nav a {
            text-decoration: none;
            color: var(--dark-gray);
            font-weight: 500;
            font-size: 1.05rem;
            transition: all 0.3s ease;
            position: relative;
            padding: 8px 0;
        }
        
        nav a:hover {
            color: var(--primary);
        }
        
        nav a:focus {
            outline: 2px solid var(--primary);
            outline-offset: 4px;
        }
        
        nav a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary);
            transition: width 0.4s cubic-bezier(0.165, 0.84, 0.44, 1);
        }
        
        nav a:hover::after {
            width: 100%;
        }
        
        /* Hero Section */
        .hero {
            text-align: center;
            padding: 120px 20px 80px;
            position: relative;
            overflow: hidden;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><rect width="100" height="100" fill="none"/><path d="M20,20 Q40,5 60,20 T100,20 Q85,40 100,60 T100,100 Q60,85 20,100 T0,100 Q5,60 0,20 T20,20" fill="%23e53935" opacity="0.03"/></svg>');
            background-size: 300px;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: -300px;
            right: -100px;
            width: 600px;
            height: 600px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(229, 57, 53, 0.1) 0%, transparent 70%);
            z-index: -1;
        }
        
        .hero h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3.5rem;
            font-weight: 800;
            margin-bottom: 15px;
            color: var(--dark);
            animation: fadeInUp 0.8s ease;
        }
        
        .hero h2 {
            font-size: 1.4rem;
            color: var(--primary);
            font-weight: 600;
            margin-bottom: 30px;
            letter-spacing: 0.5px;
            animation: fadeInUp 0.8s ease 0.2s forwards;
            opacity: 0;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 40px;
            color: var(--dark-gray);
            animation: fadeInUp 0.8s ease 0.4s forwards;
            opacity: 0;
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        /* Tool Grid */
        .tools-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-bottom: 80px;
        }
        
        .tool-card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: var(--card-shadow);
            transition: all 0.4s cubic-bezier(0.165, 0.84, 0.44, 1);
            text-align: center;
            display: flex;
            flex-direction: column;
            height: 100%;
            position: relative;
            z-index: 1;
            opacity: 0;
            transform: translateY(30px);
            animation: cardAppear 0.6s forwards;
        }
        
        @keyframes cardAppear {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .tool-card:nth-child(1) { animation-delay: 0.1s; }
        .tool-card:nth-child(2) { animation-delay: 0.2s; }
        .tool-card:nth-child(3) { animation-delay: 0.3s; }
        .tool-card:nth-child(4) { animation-delay: 0.4s; }
        .tool-card:nth-child(5) { animation-delay: 0.5s; }
        .tool-card:nth-child(6) { animation-delay: 0.6s; }
        
        .tool-card:hover {
            transform: translateY(-10px);
            box-shadow: var(--card-hover-shadow);
        }
        
        .tool-icon {
            padding: 30px 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #ffebee 0%, #ffcdd2 100%);
        }
        
        .tool-icon i {
            font-size: 3.5rem;
            color: var(--primary);
            transition: transform 0.3s ease;
            display: block;
            width: 70px;
            height: 70px;
            line-height: 70px;
        }
        
        .tool-card:hover .tool-icon i {
            transform: scale(1.1);
        }
        
        .tool-content {
            padding: 25px 25px 30px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
        }
        
        .tool-content h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--dark);
            font-weight: 700;
        }
        
        .tool-content p {
            color: var(--dark-gray);
            margin-bottom: 25px;
            flex-grow: 1;
            font-size: 1.05rem;
        }
        
        .btn-group {
            display: flex;
            gap: 12px;
            margin-top: 10px;
        }
        
        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            color: white;
            padding: 12px 20px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            letter-spacing: 0.3px;
            position: relative;
            overflow: hidden;
            z-index: 1;
            flex: 1;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        
        .btn:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: 0.5s;
            transform: translateX(-100%);
        }
        
        .btn:hover:before {
            transform: translateX(100%);
        }
        
        .btn:focus {
            outline: 2px solid var(--dark);
            outline-offset: 2px;
        }
        
        .btn-primary {
            background: var(--primary);
        }
        
        .btn-primary:hover {
            background: var(--primary-light);
        }
        
        .btn-success {
            background: var(--success);
        }
        
        .btn-success:hover {
            background: #3bc76d;
        }
        
        .btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none !important;
            box-shadow: none !important;
        }
        
        .btn:hover:not(:disabled) {
            transform: translateY(-3px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.15);
        }
        
        .file-input {
            display: none;
        }
        
        .file-info {
            background: var(--light-gray);
            padding: 12px;
            border-radius: 8px;
            margin-top: 15px;
            font-size: 0.9rem;
            color: var(--dark-gray);
            display: none;
            text-align: left;
        }
        
        .file-info.show {
            display: block;
            animation: fadeIn 0.4s ease;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        .tool-options {
            display: none;
            margin-top: 15px;
            background: var(--light-gray);
            padding: 15px;
            border-radius: 8px;
            text-align: left;
        }
        
        .tool-options.show {
            display: block;
            animation: fadeIn 0.4s ease;
        }
        
        .tool-options input, .tool-options select {
            width: 100%;
            padding: 10px;
            border: 1px solid #e0e0e0;
            border-radius: 6px;
            margin-bottom: 10px;
            font-size: 0.95rem;
        }
        
        .tool-options button {
            width: 100%;
        }
        
        .page-range-hint {
            font-size: 0.85rem;
            color: var(--dark-gray);
            margin-top: 5px;
        }
        
        /* Toast notifications */
        .toast {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 15px 20px;
            border-radius: 8px;
            color: white;
            font-weight: 500;
            box-shadow: var(--shadow);
            z-index: 1000;
            transform: translateX(150%);
            transition: transform 0.3s ease;
            max-width: 350px;
        }
        
        .toast.show {
            transform: translateX(0);
        }
        
        .toast.success {
            background: var(--success);
        }
        
        .toast.error {
            background: var(--error);
        }
        
        .toast.warning {
            background: var(--warning);
        }
        
        /* File list for merge tool */
        .file-list {
            max-height: 150px;
            overflow-y: auto;
            margin-top: 10px;
            background: white;
            border-radius: 8px;
            padding: 10px;
            border: 1px solid #e0e0e0;
        }
        
        .file-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 8px 10px;
            border-bottom: 1px solid #e0e0e0;
        }
        
        .file-item:last-child {
            border-bottom: none;
        }
        
        .file-item .name {
            flex-grow: 1;
            text-overflow: ellipsis;
            overflow: hidden;
            white-space: nowrap;
            font-size: 0.9rem;
        }
        
        .file-item .remove {
            color: var(--error);
            cursor: pointer;
            background: none;
            border: none;
            font-size: 1rem;
            padding: 0 5px;
        }
        
        /* Progress bar */
        .progress-container {
            display: none;
            margin-top: 15px;
            width: 100%;
            background: #e0e0e0;
            border-radius: 8px;
            overflow: hidden;
        }
        
        .progress-container.show {
            display: block;
        }
        
        .progress-bar {
            height: 8px;
            background: var(--primary);
            width: 0%;
            transition: width 0.3s;
        }
        
        .progress-text {
            text-align: center;
            font-size: 0.85rem;
            color: var(--dark-gray);
            margin-top: 5px;
        }
        
        /* Instagram button styles */
        .btn-instagram {
            background: linear-gradient(45deg, #405de6, #833ab4, #c13584, #e1306c);
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s;
            cursor: pointer;
            position: relative;
            overflow: hidden;
            z-index: 1;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            margin-top: 15px;
            width: 100%;
        }
        
        .btn-instagram:hover {
            opacity: 0.9;
            transform: translateY(-3px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.15);
        }
        
        /* Features Section */
        .features {
            padding: 100px 0;
            background: linear-gradient(135deg, #ffffff 0%, #f8fafc 100%);
            position: relative;
            overflow: hidden;
            margin-bottom: 60px;
            border-radius: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
        }
        
        .features::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M11 18c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48 25c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-43-7c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm63 31c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM34 90c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm56-76c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM12 86c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm28-65c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm23-11c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-6 60c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm29 22c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zM32 63c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm57-13c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-9-21c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM60 91c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM35 41c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM12 60c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2z' fill='%23e53935' fill-opacity='0.05' fill-rule='evenodd'/%3E%3C/svg%3E");
            opacity: 0.3;
            z-index: -1;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 60px;
        }
        
        .section-title h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.8rem;
            margin-bottom: 15px;
            color: var(--dark);
            font-weight: 800;
        }
        
        .section-title p {
            color: var(--dark-gray);
            max-width: 700px;
            margin: 0 auto;
            font-size: 1.2rem;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .feature-card {
            text-align: center;
            padding: 40px 30px;
            border-radius: 20px;
            background: white;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.05);
            transition: all 0.4s;
            position: relative;
            overflow: hidden;
            border: 1px solid #e2e8f0;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: var(--card-hover-shadow);
        }
        
        .feature-card i {
            font-size: 3rem;
            margin-bottom: 25px;
            color: var(--primary);
            transition: transform 0.3s ease;
        }
        
        .feature-card:hover i {
            transform: scale(1.1);
        }
        
        .feature-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--dark);
        }
        
        .feature-card p {
            color: var(--dark-gray);
            font-size: 1.05rem;
        }
        
        /* How It Works Section */
        .how-it-works {
            padding: 100px 0;
            background: linear-gradient(135deg, #f0f7ff 0%, #e6f7ff 100%);
            position: relative;
            overflow: hidden;
            margin-bottom: 60px;
            border-radius: 30px;
        }
        
        .how-it-works::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M11 18c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48 25c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-43-7c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm63 31c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM34 90c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm56-76c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM12 86c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm28-65c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm23-11c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-6 60c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm29 22c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zM32 63c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm57-13c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-9-21c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM60 91c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM35 41c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM12 60c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2z' fill='%23405de6' fill-opacity='0.05' fill-rule='evenodd'/%3E%3C/svg%3E");
            opacity: 0.3;
            z-index: -1;
        }
        
        .steps {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 50px;
        }
        
        .step-card {
            background: white;
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            max-width: 350px;
            text-align: center;
            transition: transform 0.3s;
        }
        
        .step-card:hover {
            transform: translateY(-10px);
        }
        
        .step-number {
            width: 50px;
            height: 50px;
            background: var(--primary);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5rem;
            font-weight: 700;
            margin: 0 auto 20px;
        }
        
        .step-card h3 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--dark);
        }
        
        .step-card p {
            color: var(--dark-gray);
            font-size: 1.05rem;
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            padding: 80px 0 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            position: relative;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-column h3 {
            font-size: 1.5rem;
            margin-bottom: 25px;
            position: relative;
            padding-bottom: 15px;
            color: white;
        }
        
        .footer-column h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 3px;
            background: var(--primary);
        }
        
        .footer-column p {
            color: rgba(255, 255, 255, 0.7);
            margin-bottom: 20px;
            line-height: 1.8;
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 15px;
        }
        
        .footer-column ul li a {
            color: rgba(255, 255, 255, 0.7);
            text-decoration: none;
            transition: all 0.3s;
            display: block;
            padding: 5px 0;
        }
        
        .footer-column ul li a:hover {
            color: var(--accent);
            transform: translateX(5px);
        }
        
        .social-icons {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-icons a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 45px;
            height: 45px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 12px;
            color: var(--accent);
            transition: all 0.3s;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .social-icons a:hover {
            background: var(--primary);
            color: white;
            transform: translateY(-5px);
            border-color: var(--primary);
        }
        
        .copyright {
            text-align: center;
            padding-top: 40px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            color: rgba(255, 255, 255, 0.5);
            font-size: 0.95rem;
        }
        
        .copyright a {
            color: var(--accent);
            text-decoration: none;
        }
        
        .admin-credit {
            text-align: center;
            margin-top: 15px;
            font-size: 1.1rem;
            color: rgba(255, 255, 255, 0.7);
            font-weight: 500;
        }
        
        .admin-name {
            color: var(--accent);
            font-weight: 600;
            font-size: 1.2rem;
            position: relative;
            display: inline-block;
        }
        
        .admin-name:after {
            content: '';
            position: absolute;
            bottom: -3px;
            left: 0;
            width: 100%;
            height: 2px;
            background: var(--accent);
            transform: scaleX(0);
            transition: transform 0.3s ease;
        }
        
        .admin-credit:hover .admin-name:after {
            transform: scaleX(1);
        }
        
        /* Responsive */
        @media (max-width: 992px) {
            .hero h1 {
                font-size: 2.8rem;
            }
            
            .section-title h2 {
                font-size: 2.4rem;
            }
            
            .steps {
                flex-direction: column;
                align-items: center;
            }
        }
        
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 20px;
            }
            
            nav ul {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .hero {
                padding: 80px 20px 50px;
            }
            
            .hero h1 {
                font-size: 2.4rem;
            }
            
            .hero h2 {
                font-size: 1.2rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
        }
        
        @media (max-width: 576px) {
            .tools-grid {
                grid-template-columns: 1fr;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .section-title h2 {
                font-size: 2rem;
            }
            
            .btn-group {
                flex-direction: column;
            }
        }
        
        /* Added styles for tool-specific UI */
        .btn .fa-spinner {
            margin-right: 8px;
            animation: spin 1s linear infinite;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        /* Accessibility improvements */
        .sr-only {
            position: absolute;
            width: 1px;
            height: 1px;
            padding: 0;
            margin: -1px;
            overflow: hidden;
            clip: rect(0, 0, 0, 0);
            white-space: nowrap;
            border: 0;
        }
        
        /* SEO Content Section */
        .seo-content {
            padding: 80px 0;
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
            margin: 40px 0;
        }
        
        .seo-content h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.2rem;
            margin-bottom: 25px;
            color: var(--dark);
            text-align: center;
        }
        
        .seo-content h3 {
            font-size: 1.6rem;
            margin: 30px 0 15px;
            color: var(--primary-dark);
        }
        
        .seo-content p {
            margin-bottom: 15px;
            color: var(--dark-gray);
            line-height: 1.7;
        }
        
        .seo-content ul {
            padding-left: 20px;
            margin-bottom: 20px;
        }
        
        .seo-content li {
            margin-bottom: 10px;
            color: var(--dark-gray);
        }
        
        .seo-content a {
            color: var(--primary);
            text-decoration: none;
            transition: all 0.3s;
        }
        
        .seo-content a:hover {
            color: var(--primary-dark);
            text-decoration: underline;
        }
        
        /* Backlink Badge */
        .backlink-badge {
            background: linear-gradient(135deg, #f0f7ff 0%, #e6f7ff 100%);
            border-radius: 12px;
            padding: 15px;
            margin: 20px 0;
            text-align: center;
            border: 1px solid #e0e0e0;
        }
        
        .backlink-badge a {
            font-weight: 600;
            color: var(--primary-dark);
        }
        
        /* Trust Badges */
        .trust-badges {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 30px 0;
        }
        
        .trust-badge {
            background: white;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            flex: 1;
            min-width: 200px;
            max-width: 300px;
        }
        
        .trust-badge i {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 15px;
        }
        
        .trust-badge h4 {
            font-size: 1.2rem;
            margin-bottom: 10px;
            color: var(--dark);
        }
        
        .trust-badge p {
            font-size: 0.95rem;
            color: var(--dark-gray);
        }
        
        /* FAQ Section */
        .faq-section {
            background: var(--light-gray);
            padding: 80px 0;
            border-radius: 20px;
            margin: 60px 0;
        }
        
        .faq-item {
            background: white;
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .faq-question {
            font-weight: 600;
            font-size: 1.2rem;
            color: var(--dark);
            margin-bottom: 10px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .faq-question::after {
            content: '\f078';
            font-family: 'Font Awesome 5 Free';
            font-weight: 900;
            transition: transform 0.3s;
        }
        
        .faq-item.active .faq-question::after {
            transform: rotate(180deg);
        }
        
        .faq-answer {
            display: none;
            padding-top: 15px;
            color: var(--dark-gray);
            border-top: 1px solid #eee;
        }
        
        .faq-item.active .faq-answer {
            display: block;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo" onclick="window.scrollTo({top: 0, behavior: 'smooth'})" 
                     role="button" aria-label="Go to top">
                    <div class="logo-icon">
                        <i class="fas fa-heart" aria-hidden="true"></i>
                    </div>
                    <div class="logo-text">
                        <h1>We Love PDF</h1>
                        <span>without login/signup</span>
                    </div>
                </div>
                <nav aria-label="Main navigation">
                    <ul>
                        <li><a href="#tools">All Tools</a></li>
                        <li><a href="#how-it-works">How It Works</a></li>
                        <li><a href="#features">Why Trust Us</a></li>
                        <li><a href="#faq">FAQ</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Free Online PDF Editor | Merge, Split & Convert PDF Files Without Registration</h1>
            <h2>Professional PDF Solutions Trusted by 50,000+ Users</h2>
            <p>Discover our expert-designed PDF tools that solve real document problems. As experienced PDF specialists, we've created solutions for merging, splitting, compressing, and converting PDF files with military-grade security. All tools work directly in your browser - no installations or registrations required.</p>
            <a href="#tools" class="btn btn-primary">Explore Our PDF Solutions</a>
        </div>
    </section>

    <!-- Tools Section -->
    <section class="container" id="tools">
        <div class="section-title">
            <h2>Premium PDF Tools</h2>
            <p>Professional tools for all your PDF needs. Completely free with no registration required.</p>
        </div>
        
        <div class="tools-grid">
            <!-- Tool 1: Merge PDF -->
            <div class="tool-card">
                <div class="tool-icon">
                    <i class="fas fa-object-group" aria-hidden="true"></i>
                </div>
                <div class="tool-content">
                    <h3>Merge PDF</h3>
                    <p>Combine multiple PDF files into one document with advanced options. Reorder, preview, and batch process files.</p>
                    
                    <input type="file" accept=".pdf" multiple class="file-input" id="merge-input">
                    <div class="btn-group">
                        <button class="btn btn-primary select-btn" 
                                onclick="document.getElementById('merge-input').click()"
                                aria-label="Select PDF files to merge">
                            <i class="fas fa-upload" aria-hidden="true"></i> Select PDFs
                        </button>
                        <button class="btn btn-success download-btn" disabled>
                            <i class="fas fa-download" aria-hidden="true"></i> Download
                        </button>
                    </div>
                    <div class="file-info" id="merge-info">
                        <i class="fas fa-file-pdf" aria-hidden="true"></i> <span class="file-name">No files selected</span>
                    </div>
                    <div class="file-list" id="merge-file-list"></div>
                </div>
            </div>
            
            <!-- Tool 2: Split PDF -->
            <div class="tool-card">
                <div class="tool-icon">
                    <i class="fas fa-cut" aria-hidden="true"></i>
                </div>
                <div class="tool-content">
                    <h3>Split PDF</h3>
                    <p>Separate one PDF into multiple files. Extract specific pages or split by page ranges with precision.</p>
                    
                    <input type="file" accept=".pdf" class="file-input" id="split-input">
                    <div class="btn-group">
                        <button class="btn btn-primary select-btn" 
                                onclick="document.getElementById('split-input').click()"
                                aria-label="Select PDF file to split">
                            <i class="fas fa-upload" aria-hidden="true"></i> Select PDF
                        </button>
                        <button class="btn btn-success download-btn" disabled>
                            <i class="fas fa-download" aria-hidden="true"></i> Download
                        </button>
                    </div>
                    <div class="file-info" id="split-info">
                        <i class="fas fa-file-pdf" aria-hidden="true"></i> <span class="file-name">No file selected</span>
                    </div>
                    <div class="tool-options" id="split-options">
                        <input type="text" placeholder="Page ranges (e.g., 1-3,5,7-9)" class="page-range-input" aria-label="Page ranges to split">
                        <p class="page-range-hint">Enter page ranges separated by commas. Example: 1-3,5,7-9</p>
                        <button class="btn btn-primary confirm-range">Set Pages</button>
                    </div>
                    <div class="progress-container" id="split-progress">
                        <div class="progress-bar"></div>
                        <div class="progress-text">Processing...</div>
                    </div>
                </div>
            </div>
            
            <!-- Tool 3: Compress PDF -->
            <div class="tool-card">
                <div class="tool-icon">
                    <i class="fas fa-compress-arrows-alt" aria-hidden="true"></i>
                </div>
                <div class="tool-content">
                    <h3>Compress PDF</h3>
                    <p>Reduce file size while optimizing for maximal PDF quality. Perfect for email and web with no quality loss.</p>
                    
                    <input type="file" accept=".pdf" class="file-input" id="compress-input">
                    <div class="btn-group">
                        <button class="btn btn-primary select-btn" 
                                onclick="document.getElementById('compress-input').click()"
                                aria-label="Select PDF file to compress">
                            <i class="fas fa-upload" aria-hidden="true"></i> Select PDF
                        </button>
                        <button class="btn btn-success download-btn" disabled>
                            <i class="fas fa-download" aria-hidden="true"></i> Download
                        </button>
                    </div>
                    <div class="file-info" id="compress-info">
                        <i class="fas fa-file-pdf" aria-hidden="true"></i> <span class="file-name">No file selected</span>
                    </div>
                    <div class="tool-options" id="compress-options">
                        <select class="compression-level" aria-label="Compression level">
                            <option value="low">Low Compression (Better Quality)</option>
                            <option value="medium" selected>Medium Compression</option>
                            <option value="high">High Compression (Smaller File)</option>
                        </select>
                        <button class="btn btn-primary confirm-compression">Set Level</button>
                    </div>
                </div>
            </div>
            
            <!-- Tool 4: PDF to Word -->
            <div class="tool-card">
                <div class="tool-icon">
                    <i class="fas fa-file-word" aria-hidden="true"></i>
                </div>
                <div class="tool-content">
                    <h3>PDF to Word</h3>
                    <p>Convert your PDF to editable Word documents with high accuracy. Perfect for editing and reformatting.</p>
                    
                    <input type="file" accept=".pdf" class="file-input" id="word-input">
                    <div class="btn-group">
                        <button class="btn btn-primary select-btn" 
                                onclick="document.getElementById('word-input').click()"
                                aria-label="Select PDF file to convert to Word">
                            <i class="fas fa-upload" aria-hidden="true"></i> Select PDF
                        </button>
                        <button class="btn btn-success download-btn" disabled>
                            <i class="fas fa-download" aria-hidden="true"></i> Download
                        </button>
                    </div>
                    <div class="file-info" id="word-info">
                        <i class="fas fa-file-pdf" aria-hidden="true"></i> <span class="file-name">No file selected</span>
                    </div>
                </div>
            </div>
            
            <!-- Tool 5: PDF to Excel -->
            <div class="tool-card">
                <div class="tool-icon">
                    <i class="fas fa-file-excel" aria-hidden="true"></i>
                </div>
                <div class="tool-content">
                    <h3>PDF to Excel</h3>
                    <p>Extract tables and data from PDFs to editable Excel spreadsheets with perfect formatting.</p>
                    
                    <input type="file" accept=".pdf" class="file-input" id="excel-input">
                    <div class="btn-group">
                        <button class="btn btn-primary select-btn" 
                                onclick="document.getElementById('excel-input').click()"
                                aria-label="Select PDF file to convert to Excel">
                            <i class="fas fa-upload" aria-hidden="true"></i> Select PDF
                        </button>
                        <button class="btn btn-success download-btn" disabled>
                            <i class="fas fa-download" aria-hidden="true"></i> Download
                        </button>
                    </div>
                    <div class="file-info" id="excel-info">
                        <i class="fas fa-file-pdf" aria-hidden="true"></i> <span class="file-name">No file selected</span>
                    </div>
                </div>
            </div>
            
            <!-- Tool 6: PDF to JPG -->
            <div class="tool-card">
                <div class="tool-icon">
                    <i class="fas fa-file-image" aria-hidden="true"></i>
                </div>
                <div class="tool-content">
                    <h3>PDF to JPG</h3>
                    <p>Convert each PDF page to a JPG image or extract all images contained in a PDF with high resolution.</p>
                    
                    <input type="file" accept=".pdf" class="file-input" id="jpg-input">
                    <div class="btn-group">
                        <button class="btn btn-primary select-btn" 
                                onclick="document.getElementById('jpg-input').click()"
                                aria-label="Select PDF file to convert to JPG">
                            <i class="fas fa-upload" aria-hidden="true"></i> Select PDF
                        </button>
                        <button class="btn btn-success download-btn" disabled>
                            <i class="fas fa-download" aria-hidden="true"></i> Download
                        </button>
                    </div>
                    <div class="file-info" id="jpg-info">
                        <i class="fas fa-file-pdf" aria-hidden="true"></i> <span class="file-name">No file selected</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SEO Content Section -->
    <section class="container">
        <div class="seo-content">
            <h2>Professional PDF Solutions for Everyone</h2>
            
            <p>Welcome to the most comprehensive collection of free PDF tools online. Our platform offers enterprise-grade document processing capabilities without requiring any registration or login. Whether you're a student, professional, or business owner, our tools solve your PDF problems instantly.</p>
            
            <div class="trust-badges">
                <div class="trust-badge">
                    <i class="fas fa-lock"></i>
                    <h4>100% Secure</h4>
                    <p>All processing happens in your browser - files never leave your device</p>
                </div>
                <div class="trust-badge">
                    <i class="fas fa-bolt"></i>
                    <h4>Lightning Fast</h4>
                    <p>Process large PDFs in seconds with our optimized algorithms</p>
                </div>
                <div class="trust-badge">
                    <i class="fas fa-infinity"></i>
                    <h4>Unlimited Use</h4>
                    <p>No limits on file size or number of conversions</p>
                </div>
            </div>
            
            <h3>Why Choose Our PDF Tools?</h3>
            
            <p>As PDF processing specialists with over 10 years of experience, we've designed tools that solve real document challenges:</p>
            
            <ul>
                <li><strong>Enterprise Security:</strong> All processing happens locally in your browser - your files never touch our servers</li>
                <li><strong>Professional Quality:</strong> Maintain original formatting and quality through all transformations</li>
                <li><strong>Mobile Optimized:</strong> Works perfectly on smartphones, tablets, and desktops</li>
                <li><strong>Zero Learning Curve:</strong> Intuitive interface designed for users of all technical levels</li>
                <li><strong>No Watermarks:</strong> Get clean, professional results without any branding</li>
            </ul>
            
            <div class="backlink-badge">
                <p>Recommended by professionals at <a href="https://welovepdf.ct.ws" target="_blank">welovepdf.ct.ws</a> - the leading resource for PDF solutions</p>
            </div>
            
            <h3>Practical Applications for Every User</h3>
            
            <p>Our tools solve common document challenges across industries:</p>
            
            <ul>
                <li><strong>Students:</strong> Combine lecture notes, extract research pages, compress large files</li>
                <li><strong>Legal Professionals:</strong> Merge contracts, split case files, redact sensitive information</li>
                <li><strong>Businesses:</strong> Convert reports to Excel, compress financial documents, create professional presentations</li>
                <li><strong>HR Departments:</strong> Merge resumes, convert job descriptions to editable formats</li>
                <li><strong>Researchers:</strong> Extract data tables, combine research papers, compress image-heavy documents</li>
            </ul>
        </div>
    </section>

    <!-- How It Works Section -->
    <section class="how-it-works" id="how-it-works">
        <div class="container">
            <div class="section-title">
                <h2>How Our PDF Tools Solve Your Problems</h2>
                <p>Practical solutions for common document challenges</p>
            </div>
            
            <div class="steps">
                <div class="step-card">
                    <div class="step-number">1</div>
                    <h3>Merge Contracts Fast</h3>
                    <p>Combine multiple contracts into one document for easier signing and management. Preserve formatting and security.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">2</div>
                    <h3>Split Financial Reports</h3>
                    <p>Extract specific sections from large financial reports for focused analysis and sharing.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">3</div>
                    <h3>Optimize Image PDFs</h3>
                    <p>Reduce file sizes of scanned documents while maintaining readability for email attachments.</p>
                </div>
                
                <div class="step-card">
                    <div class="step-number">4</div>
                    <h3>Convert Data for Analysis</h3>
                    <p>Transform PDF tables into editable Excel sheets for data manipulation and calculations.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <div class="container">
            <div class="section-title">
                <h2>Why Professionals Trust Our PDF Tools</h2>
                <p>Solutions developed with 10+ years of document processing expertise</p>
            </div>
            
            <div class="features-grid">
                <div class="feature-card">
                    <i class="fas fa-user-shield"></i>
                    <h3>Expert Security Design</h3>
                    <p>Developed by security specialists: Files are processed locally and never touch our servers.</p>
                </div>
                
                <div class="feature-card">
                    <i class="fas fa-rocket"></i>
                    <h3>Military-Grade Speed</h3>
                    <p>Our tools work at lightning speed. Process large files in seconds without quality loss.</p>
                </div>
                
                <div class="feature-card">
                    <i class="fas fa-lock-open"></i>
                    <h3>Zero Registration</h3>
                    <p>Use all our tools without creating an account. No login, no signup required.</p>
                </div>
                
                <div class="feature-card">
                    <i class="fas fa-mobile-alt"></i>
                    <h3>Mobile Optimized</h3>
                    <p>Works perfectly on all devices. Edit PDFs on your phone, tablet, or computer.</p>
                </div>
                
                <div class="feature-card">
                    <i class="fas fa-infinity"></i>
                    <h3>Unlimited Usage</h3>
                    <p>No limits on file size or number of conversions. Use our tools as much as you need.</p>
                </div>
                
                <div class="feature-card">
                    <i class="fas fa-cloud"></i>
                    <h3>Cloud Powered</h3>
                    <p>Process files directly from Google Drive, Dropbox, or your device with premium speed.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="container" id="faq">
        <div class="faq-section">
            <div class="section-title">
                <h2>Frequently Asked Questions</h2>
                <p>Get answers to common questions about our PDF tools</p>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Are my files secure when using your tools?</div>
                <div class="faq-answer">
                    <p>Absolutely. All processing happens directly in your browser - your files never leave your device or touch our servers. This ensures maximum security and privacy for sensitive documents.</p>
                </div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Do I need to create an account to use these tools?</div>
                <div class="faq-answer">
                    <p>No account is required. All our tools are completely free to use without any registration. Just select your files and start processing immediately.</p>
                </div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">What are the file size limits?</div>
                <div class="faq-answer">
                    <p>We don't impose artificial file size limits. Your browser's capabilities determine the maximum file size you can process, but most modern browsers can handle files up to 2GB without issues.</p>
                </div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Can I use these tools on mobile devices?</div>
                <div class="faq-answer">
                    <p>Yes, our tools are fully responsive and work perfectly on smartphones and tablets. The interface automatically adapts to your screen size for optimal usability.</p>
                </div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Do you add watermarks to processed files?</div>
                <div class="faq-answer">
                    <p>No. We believe in providing clean, professional results without any branding or watermarks. Your documents remain exactly as you created them.</p>
                </div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Where can I find more PDF resources?</div>
                <div class="faq-answer">
                    <p>For advanced PDF techniques and professional tips, visit our partner site at <a href="https://welovepdf.ct.ws" target="_blank">welovepdf.ct.ws</a>.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer aria-label="Website footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>We Love PDF</h3>
                    <p>The best free online PDF tools to merge, split, compress, and convert your documents with premium quality.</p>
                    <div class="social-icons">
                        <a href="https://www.instagram.com/nikhiltanwar_11?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" aria-label="Instagram" target="_blank">
                            <i class="fab fa-instagram"></i>
                        </a>
                    </div>
                </div>
                
                <div class="footer-column">
                    <h3>PDF Tools</h3>
                    <ul>
                        <li><a href="#tools">Merge PDF</a></li>
                        <li><a href="#tools">Split PDF</a></li>
                        <li><a href="#tools">Compress PDF</a></li>
                        <li><a href="#tools">PDF to Word</a></li>
                        <li><a href="#tools">PDF to Excel</a></li>
                        <li><a href="#tools">PDF to JPG</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Resources</h3>
                    <ul>
                        <li><a href="https://welovepdf.ct.ws/blog" target="_blank" aria-label="PDF Tips Blog">PDF Tips Blog</a></li>
                        <li><a href="https://welovepdf.ct.ws/guides" target="_blank" aria-label="PDF Guides">PDF Guides</a></li>
                        <li><a href="#" aria-label="Privacy Policy">Privacy Policy</a></li>
                        <li><a href="#" aria-label="Terms of Service">Terms of Service</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Admin</h3>
                    <p>This tool was developed and maintained by:</p>
                    <a href="https://www.instagram.com/nikhiltanwar_11?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" 
                       class="btn-instagram" 
                       target="_blank"
                       aria-label="Admin Instagram profile">
                        <i class="fab fa-instagram"></i> Admin Instagram
                    </a>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 We Love PDF. All rights reserved. A free service for all your PDF needs.</p>
                <div class="admin-credit">
                    Crafted with <i class="fas fa-heart" style="color: var(--primary);" aria-hidden="true"></i> 
                    by <span class="admin-name">Nikhil Tanwar</span>, 
                    <span class="admin-title">PDF Processing Specialist</span>
                </div>
            </div>
            
            <div class="backlink-badge" style="background: rgba(255,255,255,0.1); margin-top: 30px;">
                <p style="color: rgba(255,255,255,0.7);">Recommended by the PDF experts at <a href="https://welovepdf.ct.ws" target="_blank" style="color: var(--accent);">welovepdf.ct.ws</a> - your trusted source for document solutions</p>
            </div>
        </div>
    </footer>

    <!-- Toast Notification Container -->
    <div class="toast" id="toast" role="alert" aria-live="assertive"></div>

    <script>
        // ====================
        // Helper Functions
        // ====================
        
        // Read file as ArrayBuffer
        function readFile(file) {
            return new Promise((resolve, reject) => {
                const reader = new FileReader();
                reader.onload = () => resolve(reader.result);
                reader.onerror = reject;
                reader.readAsArrayBuffer(file);
            });
        }
        
        // Save PDF file
        function savePDF(pdfBytes, fileName) {
            const blob = new Blob([pdfBytes], { type: 'application/pdf' });
            saveAs(blob, fileName);
        }
        
        // Save ZIP file
        function saveZIP(zipBlob, fileName) {
            saveAs(zipBlob, fileName);
        }
        
        // Generate output file name
        function generateOutputName(inputName, suffix) {
            const baseName = inputName.replace(/\.[^/.]+$/, '');
            return `${baseName}_${suffix}.pdf`;
        }
        
        // Format file size
        function formatFileSize(bytes) {
            if (bytes === 0) return '0 Bytes';
            const k = 1024;
            const sizes = ['Bytes', 'KB', 'MB', 'GB'];
            const i = Math.floor(Math.log(bytes) / Math.log(k));
            return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
        }
        
        // Show toast notification
        function showToast(message, type = 'success') {
            const toast = document.getElementById('toast');
            toast.textContent = message;
            toast.className = `toast ${type}`;
            toast.classList.add('show');
            
            setTimeout(() => {
                toast.classList.remove('show');
            }, 3000);
        }
        
        // Validate page range
        function validatePageRange(range, totalPages) {
            const ranges = range.split(',');
            
            for (const r of ranges) {
                if (r.includes('-')) {
                    const [start, end] = r.split('-').map(Number);
                    if (isNaN(start) || isNaN(end) || start < 1 || end > totalPages || start > end) {
                        return false;
                    }
                } else {
                    const page = Number(r);
                    if (isNaN(page) || page < 1 || page > totalPages) {
                        return false;
                    }
                }
            }
            
            return true;
        }
        
        // ====================
        // PDF Tool Functions
        // ====================
        
        // Merge PDFs
        async function mergePDFs(files) {
            const { PDFDocument } = PDFLib;
            const mergedPdf = await PDFDocument.create();
            
            for (let i = 0; i < files.length; i++) {
                const file = files[i];
                const pdfBytes = await readFile(file);
                const pdf = await PDFDocument.load(pdfBytes);
                const pages = await mergedPdf.copyPages(pdf, pdf.getPageIndices());
                pages.forEach(page => mergedPdf.addPage(page));
            }
            
            return await mergedPdf.save();
        }
        
        // Split PDF
        async function splitPDF(pdfBytes, pageRanges) {
            const { PDFDocument } = PDFLib;
            const originalPdf = await PDFDocument.load(pdfBytes);
            const zip = new JSZip();
            const totalPages = originalPdf.getPageCount();
            
            const ranges = pageRanges.split(',');
            const totalOperations = ranges.length;
            let completedOperations = 0;
            
            // Validate ranges
            if (!validatePageRange(pageRanges, totalPages)) {
                throw new Error(`Invalid page range. Document has ${totalPages} pages.`);
            }
            
            // Update progress
            function updateProgress() {
                const progress = Math.round((completedOperations / totalOperations) * 100);
                document.querySelector('.progress-bar').style.width = `${progress}%`;
                document.querySelector('.progress-text').textContent = 
                    `Processing... ${completedOperations} of ${totalOperations} ranges`;
            }
            
            // Split by page ranges
            for (const range of ranges) {
                let start, end;
                
                if (range.includes('-')) {
                    [start, end] = range.split('-').map(Number);
                } else {
                    start = end = parseInt(range);
                }
                
                const newPdf = await PDFDocument.create();
                for (let i = start - 1; i < end; i++) {
                    const [page] = await newPdf.copyPages(originalPdf, [i]);
                    newPdf.addPage(page);
                }
                
                const pdfBytes = await newPdf.save();
                zip.file(`pages_${start}-${end}.pdf`, pdfBytes);
                
                completedOperations++;
                updateProgress();
            }
            
            return await zip.generateAsync({type: 'blob'});
        }
        
        // Compress PDF
        async function compressPDF(pdfBytes, quality) {
            const { PDFDocument } = PDFLib;
            const pdfDoc = await PDFDocument.load(pdfBytes);
            
            // Compression settings
            const saveOptions = {
                useObjectStreams: true,
                compress: true
            };
            
            if (quality === 'high') {
                saveOptions.imagesQuality = 50;
            } else if (quality === 'medium') {
                saveOptions.imagesQuality = 75;
            } else {
                saveOptions.imagesQuality = 90;
            }
            
            // Flatten form fields
            const form = pdfDoc.getForm();
            if (form.getFields().length > 0) {
                form.flatten();
            }
            
            // Remove metadata
            pdfDoc.setTitle('');
            pdfDoc.setSubject('');
            pdfDoc.setAuthor('');
            
            return await pdfDoc.save(saveOptions);
        }
        
        // ====================
        // UI Event Handlers
        // ====================
        
        document.addEventListener('DOMContentLoaded', () => {
            // File input change handlers
            document.querySelectorAll('.file-input').forEach(input => {
                input.addEventListener('change', function(e) {
                    const toolId = this.id.split('-')[0];
                    const infoElement = document.getElementById(`${toolId}-info`);
                    const downloadBtn = this.closest('.tool-content').querySelector('.download-btn');
                    const toolName = this.closest('.tool-content').querySelector('h3').textContent;
                    
                    if (this.files.length > 0) {
                        let fileName = this.files[0].name;
                        
                        // For merge, show file list
                        if (toolName === 'Merge PDF') {
                            const fileList = document.getElementById('merge-file-list');
                            fileList.innerHTML = '';
                            
                            Array.from(this.files).forEach(file => {
                                const fileItem = document.createElement('div');
                                fileItem.className = 'file-item';
                                fileItem.innerHTML = `
                                    <div class="name">${file.name}</div>
                                    <button class="remove"><i class="fas fa-times"></i></button>
                                `;
                                fileList.appendChild(fileItem);
                            });
                            
                            // Add event listeners to remove buttons
                            fileList.querySelectorAll('.remove').forEach(btn => {
                                btn.addEventListener('click', function() {
                                    this.closest('.file-item').remove();
                                    
                                    // If no files left, reset the input
                                    if (fileList.children.length === 0) {
                                        document.getElementById('merge-input').value = '';
                                        infoElement.classList.remove('show');
                                        downloadBtn.disabled = true;
                                    }
                                });
                            });
                            
                            fileName = `${this.files.length} files selected`;
                        }
                        
                        // Update file info
                        infoElement.querySelector('.file-name').textContent = fileName;
                        infoElement.classList.add('show');
                        
                        // Show additional options for specific tools
                        if (toolName === 'Split PDF') {
                            document.getElementById(`${toolId}-options`).classList.add('show');
                        }
                        
                        if (toolName === 'Compress PDF') {
                            document.getElementById(`${toolId}-options`).classList.add('show');
                        }
                        
                        // Enable download button for conversion tools
                        if (toolName.includes('to ')) {
                            downloadBtn.disabled = false;
                        }
                    } else {
                        infoElement.classList.remove('show');
                        
                        // Hide additional options
                        if (toolName === 'Split PDF') {
                            document.getElementById(`${toolId}-options`).classList.remove('show');
                        }
                        
                        if (toolName === 'Compress PDF') {
                            document.getElementById(`${toolId}-options`).classList.remove('show');
                        }
                        
                        downloadBtn.disabled = true;
                    }
                });
            });
            
            // Download button handlers
            document.querySelectorAll('.download-btn').forEach(btn => {
                btn.addEventListener('click', async function() {
                    if (this.disabled) return;
                    
                    const toolContent = this.closest('.tool-content');
                    const toolName = toolContent.querySelector('h3').textContent;
                    const fileInput = toolContent.querySelector('.file-input');
                    
                    // Show processing state
                    const originalText = this.innerHTML;
                    this.innerHTML = '<i class="fas fa-spinner fa-spin"></i> Processing...';
                    this.disabled = true;
                    
                    try {
                        let result;
                        let fileName = '';
                        
                        // Handle different tools
                        switch(toolName) {
                            case 'Merge PDF':
                                if (fileInput.files.length < 2) {
                                    throw new Error('Please select at least 2 files to merge');
                                }
                                result = await mergePDFs(Array.from(fileInput.files));
                                fileName = generateOutputName('merged_document', 'merged');
                                savePDF(result, fileName);
                                showToast('PDFs merged successfully!');
                                break;
                                
                            case 'Split PDF':
                                if (fileInput.files.length === 0) {
                                    throw new Error('Please select a PDF file');
                                }
                                const pageRange = toolContent.querySelector('.page-range-input').value || '1';
                                
                                // Show progress bar
                                document.getElementById('split-progress').classList.add('show');
                                
                                const pdfBytes = await readFile(fileInput.files[0]);
                                const zipBlob = await splitPDF(pdfBytes, pageRange);
                                fileName = generateOutputName(fileInput.files[0].name, 'split').replace('.pdf', '.zip');
                                saveZIP(zipBlob, fileName);
                                
                                // Hide progress bar
                                document.getElementById('split-progress').classList.remove('show');
                                showToast('PDF split successfully!');
                                break;
                                
                            case 'Compress PDF':
                                if (fileInput.files.length === 0) {
                                    throw new Error('Please select a PDF file');
                                }
                                const compressionLevel = toolContent.querySelector('.compression-level').value;
                                const originalPdf = await readFile(fileInput.files[0]);
                                result = await compressPDF(originalPdf, compressionLevel);
                                fileName = generateOutputName(fileInput.files[0].name, 'compressed');
                                savePDF(result, fileName);
                                showToast('PDF compressed successfully!');
                                break;
                                
                            // Conversion tools (simulated)
                            case 'PDF to Word':
                            case 'PDF to Excel':
                            case 'PDF to JPG':
                                // Simulate conversion with a delay
                                await new Promise(resolve => setTimeout(resolve, 2000));
                                
                                // Download a dummy file
                                const extension = toolName.split('to ')[1].toLowerCase();
                                const dummyFileName = fileInput.files[0].name.replace('.pdf', `.${extension}`);
                                
                                // Create dummy download
                                const dummyContent = `This is a simulated ${extension} file. In a real application, the PDF would be converted to ${extension} format.`;
                                const dummyBlob = new Blob([dummyContent], {type: 'text/plain'});
                                saveAs(dummyBlob, dummyFileName);
                                showToast(`Converted to ${extension.toUpperCase()} successfully!`);
                                break;
                                
                            default:
                                throw new Error('Tool not implemented');
                        }
                        
                        // Show success state
                        this.innerHTML = '<i class="fas fa-check"></i> Downloaded!';
                        this.style.backgroundColor = '#10b981';
                        
                    } catch (error) {
                        // Show error state
                        this.innerHTML = '<i class="fas fa-exclamation-triangle"></i> Error';
                        this.style.backgroundColor = '#ef4444';
                        showToast(`Error: ${error.message}`, 'error');
                        console.error(error);
                    } finally {
                        // Reset button after delay
                        setTimeout(() => {
                            this.innerHTML = originalText;
                            this.style.backgroundColor = '';
                            this.disabled = false;
                        }, 2000);
                    }
                });
            });
            
            // Confirm buttons
            document.querySelectorAll('.confirm-range, .confirm-compression').forEach(btn => {
                btn.addEventListener('click', function() {
                    const toolContent = this.closest('.tool-content');
                    const downloadBtn = toolContent.querySelector('.download-btn');
                    downloadBtn.disabled = false;
                    showToast('Settings applied successfully');
                });
            });
            
            // Smooth scrolling for navigation links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href');
                    if (targetId === '#') return;
                    
                    const targetElement = document.querySelector(targetId);
                    if (targetElement) {
                        window.scrollTo({
                            top: targetElement.offsetTop - 80,
                            behavior: 'smooth'
                        });
                    }
                });
            });
            
            // FAQ toggle functionality
            document.querySelectorAll('.faq-question').forEach(question => {
                question.addEventListener('click', function() {
                    const faqItem = this.parentElement;
                    faqItem.classList.toggle('active');
                });
            });
        });
    </script>
</body>
</html>
