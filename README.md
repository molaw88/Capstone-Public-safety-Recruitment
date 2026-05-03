<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOC Recruitment: Systemic Modernization | Moses Zenon-Laguerre</title>
    <style>
        :root {
            --bay-blue: #14558F; /* Primary MA Brand Color */
            --berkshires-green: #388557; /* Accent Green */
            --duckling-yellow: #F6C51B; /* Highlight Yellow */
            --granite-gray: #F2F2F2; /* Light Background Gray */
            --text-dark: #333333;
            --white: #FFFFFF;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: "Times New Roman", Times, serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: var(--white);
            scroll-behavior: smooth;
        }

        /* Clean Section Transitions - No gaps */
        section {
            padding: 80px 10% ;
            min-height: 90vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            border-bottom: 1px solid #ddd;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            width: 100%;
        }

        /* Header Style */
        .hero-section {
            background-color: var(--bay-blue);
            color: var(--white);
            text-align: left;
            border-bottom: 8px solid var(--duckling-yellow);
        }

        h1 {
            font-size: 3.5rem;
            margin-bottom: 0.5rem;
            line-height: 1.1;
        }

        h2 {
            color: var(--bay-blue);
            font-size: 2.2rem;
            margin-bottom: 1.5rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .subtitle {
            font-size: 1.5rem;
            opacity: 0.9;
            margin-bottom: 2rem;
        }

        .author-info {
            border-top: 1px solid rgba(255,255,255,0.3);
            padding-top: 20px;
            margin-top: 30px;
        }

        /* Funnel Component - Clean State Style */
        .funnel-container {
            margin: 40px 0;
        }

        .funnel-step {
            background: var(--granite-gray);
            border-left: 6px solid var(--bay-blue);
            margin-bottom: 5px;
            padding: 20px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 1.2rem;
            transition: background 0.3s;
        }

        .funnel-step:hover {
            background: #e9e9e9;
        }

        .funnel-step strong {
            color: var(--bay-blue);
            font-size: 1.5rem;
        }

        .success-step {
            border-left-color: var(--berkshires-green);
            background: #e8f5e9;
        }

        /* Grid for Metrics */
        .metrics-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .metric-card {
            background: var(--white);
            border: 1px solid #ccc;
            padding: 30px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }

        .metric-card span {
            display: block;
            font-size: 3rem;
            font-weight: bold;
            color: var(--bay-blue);
            margin-bottom: 10px;
        }

        .highlight-box {
            background: var(--granite-gray);
            padding: 40px;
            border-radius: 4px;
            margin: 20px 0;
            border-top: 4px solid var(--bay-blue);
        }

        footer {
            background: #333;
            color: white;
            padding: 40px 10%;
            text-align: center;
            font-size: 0.9rem;
        }

        /* Animations */
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }

        @media (max-width: 768px) {
            h1 { font-size: 2.5rem; }
            section { padding: 50px 5%; }
        }
    </style>
</head>
<body>

    <section class="hero-section">
        <div class="container">
            <p style="text-transform: uppercase; letter-spacing: 2px; font-weight: bold; margin-bottom: 10px; color: var(--duckling-yellow);">MPA Capstone Senior Leadership</p>
            <h1>Diagnosing and Modernizing the Public-Safety Hiring Process</h1>
            <p class="subtitle">A Systems Approach to Workforce Stability</p>
            
            <div class="author-info">
                <strong>Moses Zenon-Laguerre</strong><br>
                Massachusetts Department of Correction | Clark University<br>
                May 4th, 2026
            </div>
        </div>
    </section>

    <section>
        <div class="container fade-in">
            <h2>The Velocity Deficit</h2>
            <p style="font-size: 1.4rem;">The recruitment challenges facing the DOC are not a result of declining applicant interest, but the product of a <strong>structurally misaligned hiring system</strong>.</p>
            
            <div class="highlight-box">
                <p>Specifically, the interaction between high-velocity engagement (the <strong>Fast Loop</strong>) and a structurally constrained administrative system (the <strong>Slow Loop</strong>) creates a measurable deficit in candidate momentum.</p>
            </div>
        </div>
    </section>

    <section style="background-color: var(--granite-gray);">
        <div class="container fade-in">
            <h2>01. The Yield Gap (Cohort 339)</h2>
            <p>We lose the majority of candidates to <strong>Psychological Attrition</strong>—withdrawal driven by disengagement rather than disqualification.</p>
            
            <div class="funnel-container">
                <div class="funnel-step"><span>Initial Database Leads</span> <strong>2,000</strong></div>
                <div class="funnel-step"><span>Registered for Exam</span> <strong>800</strong></div>
                <div class="funnel-step"><span>Listed on Eligible Roster</span> <strong>600</strong></div>
                <div class="funnel-step success-step"><span>Academy Entry</span> <strong style="color:var(--berkshires-green)">150</strong></div>
            </div>
            <p style="font-style: italic; font-size: 0.9rem;">*Only 7.5% of total leads convert to hires.</p>
        </div>
    </section>

    <section>
        <div class="container fade-in">
            <h2>02. The "Dead Time" Audit</h2>
            <p>Administrative latency is the primary source of resistance, reducing system throughput.</p>
            
            <div class="metrics-grid">
                <div class="metric-card">
                    <span>90 Days</span>
                    <p>Total systemic silence between hiring milestones.</p>
                </div>
                <div class="metric-card">
                    <span>10.2 Mo.</span>
                    <p>Average total months to process a candidate.</p>
                </div>
                <div class="metric-card">
                    <span>4-6 Mo.</span>
                    <p><strong>Candidate Half-Life</strong>: The point at which 50% of the pool disengages.</p>
                </div>
            </div>
        </div>
    </section>

    <section style="background-color: var(--bay-blue); color: white;">
        <div class="container fade-in">
            <h2 style="color: var(--duckling-yellow);">03. Strategic Modernization</h2>
            <p style="font-size: 1.2rem; margin-bottom: 20px;">Moving from reactive hiring to an <strong>Engineered Workforce Flow</strong>.</p>
            
            <div class="metrics-grid">
                <div style="background: rgba(255,255,255,0.1); padding: 20px; border-top: 4px solid var(--duckling-yellow);">
                    <h3 style="margin-bottom: 10px;">Immediate Action</h3>
                    <p>Enforce a <strong>7-day contact rule</strong>. No candidate goes more than a week without a touchpoint.</p>
                </div>
                <div style="background: rgba(255,255,255,0.1); padding: 20px; border-top: 4px solid var(--duckling-yellow);">
                    <h3 style="margin-bottom: 10px;">System Alignment</h3>
                    <p>Synchronize outreach with exam registration cycles and background check milestones.</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container fade-in" style="text-align: center;">
            <h2>Conclusion</h2>
            <p style="font-size: 1.8rem; line-height: 1.3;">The system fails not because candidates are unavailable, but because it is unable to <strong>retain</strong> them.</p>
            <p style="margin-top: 20px;">We must transition from an input problem to a <strong>system performance problem</strong>.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Moses Zenon-Laguerre | Clark University MPA Capstone</p>
    </footer>

    <script>
        // Simple Intersection Observer for Fade-In Effects
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.1 });

       document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
    </script>
</body>
</html>
