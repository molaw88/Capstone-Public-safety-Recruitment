<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOC Recruitment: Systemic Modernization | Moses Zenon-Laguerre</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet">
    <style>
        :root {
            --bg-dark: #050b14;
            --bg-card: #0d1a2d;
            --accent-orange: #FF8C42;
            --accent-green: #4CAF50;
            --text-main: #F4F4F4;
            --text-dim: #a0aec0;
            --border-glass: rgba(255, 255, 255, 0.1);
        }

        body {
            margin: 0;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: var(--bg-dark);
            color: var(--text-main);
            scroll-behavior: smooth;
        }

        section {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 80px 20px;
            box-sizing: border-box;
        }

        .container { max-width: 1100px; width: 100%; }

        /* HERO SECTION */
        .hero-title { font-size: clamp(2.5rem, 6vw, 4.5rem); font-weight: 800; line-height: 1.1; margin-bottom: 10px; }
        .hero-subtitle { font-size: 1.5rem; color: var(--accent-orange); letter-spacing: 2px; text-transform: uppercase; margin-bottom: 30px; display: block; }
        .author-tag { font-size: 1.1rem; border-left: 3px solid var(--accent-green); padding-left: 15px; margin-top: 40px; color: var(--text-dim); }

        /* DATA CARDS */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; margin-top: 40px; }
        .card { 
            background: var(--bg-card); 
            padding: 40px; 
            border-radius: 12px; 
            border: 1px solid var(--border-glass);
            transition: transform 0.3s ease;
        }
        .card:hover { transform: translateY(-5px); border-color: var(--accent-orange); }
        .card h3 { color: var(--accent-orange); margin-top: 0; text-transform: uppercase; font-size: 0.9rem; letter-spacing: 1.5px; }
        .card .big-num { font-size: 3.5rem; font-weight: 800; display: block; margin: 10px 0; }

        /* FUNNEL DESIGN */
        .funnel-box {
            background: linear-gradient(90deg, #162a45 0%, #0d1a2d 100%);
            margin: 8px 0;
            padding: 20px 30px;
            border-left: 5px solid var(--accent-orange);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        /* UTILITY */
        .highlight { color: var(--accent-orange); }
        .reveal { opacity: 0; transform: translateY(30px); transition: all 0.8s ease-out; }
        .reveal.active { opacity: 1; transform: translateY(0); }
        
        footer { 
            padding: 60px; 
            text-align: center; 
            border-top: 1px solid var(--border-glass); 
            font-size: 0.9rem; 
            color: var(--text-dim);
        }
    </style>
</head>
<body>

    <section>
        <div class="container animate__animated animate__fadeIn">
            <span class="hero-subtitle">MPA Capstone Senior Leadership</span>
            <h1 class="hero-title">Diagnosing and <span class="highlight">Modernizing</span><br>the Public-Safety Hiring Process</h1>
            <p style="font-size: 1.3rem; max-width: 800px;">A System Approach to workforce stability within the Massachusetts Department of Correction.</p>
            
            <div class="author-tag">
                <strong>Moses Zenon-Laguerre</strong><br>
                Clark University | May 4th, 2026
            </div>
        </div>
    </section>

    <section style="background: #081220;">
        <div class="container reveal">
            <h2 style="color: var(--accent-orange);">The Thesis</h2>
            <p style="font-size: 1.8rem; line-height: 1.4; font-weight: 600;">
                The recruitment challenge is not a <span class="highlight">Labor Supply</span> problem—it is a <span class="highlight">System Design</span> problem.
            </p>
            [span_2](start_span)[span_3](start_span)<p>This study identifies the <strong>Velocity Deficit</strong>: a collapse in candidate momentum caused by the misalignment between engagement and administrative processing[span_2](end_span)[span_3](end_span).</p>
        </div>
    </section>

    <section>
        <div class="container reveal">
            <h2 style="color: var(--accent-orange);">01. The Yield Gap</h2>
            <p>Analysis of <strong>Cohort 339</strong> shows that the majority of attrition is <em>Psychological</em>, not <em>Technical</em>. [span_4](start_span)Candidates disengage due to latency[span_4](end_span).</p>
            
            <div style="margin-top: 40px;">
                <div class="funnel-box" style="width: 100%;"><span>Initial Database (Leads)</span> <strong>2,000</strong></div>
                <div class="funnel-box" style="width: 85%;"><span>Registered for Exam</span> <strong>800</strong></div>
                <div class="funnel-box" style="width: 70%;"><span>Listed on Eligible Roster</span> <strong>600</strong></div>
                <div class="funnel-box" style="width: 35%; border-left-color: var(--accent-green); background: rgba(76, 175, 80, 0.1);">
                    <span>Academy Entry</span> <strong style="color: var(--accent-green);">150</strong>
                </div>
            </div>
            [span_5](start_span)<p style="font-size: 0.9rem; color: var(--text-dim); margin-top: 20px;">*Final system throughput accounts for a 92% total attrition rate[span_5](end_span).</p>
        </div>
    </section>

    <section style="background: #081220;">
        <div class="container reveal">
            <h2 style="color: var(--accent-orange);">02. System Variables</h2>
            [span_6](start_span)[span_7](start_span)<p>We measured the resistance within the "Slow Loop" to identify structural bottlenecks[span_6](end_span)[span_7](end_span).</p>
            
            <div class="grid">
                <div class="card">
                    <h3>Dead Time</h3>
                    <span class="big-num">90</span>
                    [span_8](start_span)<p>Days of systemic silence between registration and examination[span_8](end_span).</p>
                </div>
                <div class="card">
                    <h3>Candidate Half-Life</h3>
                    <span class="big-num">4-6</span>
                    [span_9](start_span)<p>Months until 50% of the candidate pool disengages[span_9](end_span).</p>
                </div>
                <div class="card">
                    <h3>Avg. Time-to-Hire</h3>
                    <span class="big-num">10.2</span>
                    [span_10](start_span)<p>Months to process a single candidate through the legacy system[span_10](end_span).</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container reveal">
            <h2 style="color: var(--accent-orange);">03. The Strategic Shift</h2>
            [span_11](start_span)<p>Moving from a <strong>Reactive Posture</strong> to a <strong>Predictive Talent Engine</strong>[span_11](end_span).</p>
            
            <div class="grid">
                <div class="card" style="border-top: 4px solid var(--accent-green);">
                    <h3>The Fast Loop</h3>
                    <p>High-velocity engagement. [span_12](start_span)[span_13](start_span)Enforcing a <strong>7-day contact rule</strong> and aggressive outreach to maintain momentum[span_12](end_span)[span_13](end_span).</p>
                </div>
                <div class="card" style="border-top: 4px solid var(--accent-orange);">
                    <h3>The Slow Loop</h3>
                    <p>Administrative optimization. [span_14](start_span)[span_15](start_span)Aligning civil service cycles with engagement velocity to reduce the deficit[span_14](end_span)[span_15](end_span).</p>
                </div>
            </div>
        </div>
    </section>

    <section style="background: linear-gradient(180deg, var(--bg-dark) 0%, #0a1b33 100%);">
        <div class="container reveal" style="text-align: center;">
            <h1 style="font-size: 3.5rem;">Ready for <span style="color: var(--accent-green);">Stability</span>.</h1>
            [span_16](start_span)[span_17](start_span)<p style="margin: 20px auto; max-width: 700px;">Success is not determined by the number of candidates entering the system, but by the system's ability to <strong>retain</strong> them[span_16](end_span)[span_17](end_span).</p>
        </div>
    </section>

    <footer>
        <p><strong>Moses Zenon-Laguerre</strong> | Master of Public Administration Capstone</p>
        <p style="opacity: 0.5; margin-top: 10px;">Clark University &copy; 2026</p>
    </footer>

    <script>
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) entry.target.classList.add('active');
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
    </script>
</body>
</html>
