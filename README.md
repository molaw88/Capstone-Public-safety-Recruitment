<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOC Recruitment: Systemic Modernization | Moses Zenon-Laguerre</title>
    <style>
        :root {
            --bay-blue: #14558F;
            --berkshires-green: #388557;
            --duckling-yellow: #F6C51B;
            --granite-gray: #F2F2F2;
            --text-dark: #333333;
            --white: #FFFFFF;
            --danger-red: #C62828;
            --shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        * { box-sizing: border-box; margin: 0; padding: 0; }

        body {
            font-family: "Times New Roman", Times, serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: var(--white);
            scroll-behavior: smooth;
        }

        #progress-container { position: fixed; top: 0; width: 100%; height: 6px; background: #ccc; z-index: 1000; }
        #progress-bar { height: 6px; background: var(--duckling-yellow); width: 0%; transition: width 0.1s; }

        section {
            padding: 80px 10%;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            border-bottom: 1px solid #ddd;
        }

        .container { max-width: 1100px; margin: 0 auto; width: 100%; }

        h1 { font-size: 3.8rem; line-height: 1.1; color: var(--white); margin-bottom: 10px; }
        h2 { color: var(--bay-blue); font-size: 2.8rem; margin-bottom: 30px; text-transform: uppercase; border-left: 12px solid var(--duckling-yellow); padding-left: 25px; }

        .hero-section { background-color: var(--bay-blue); color: var(--white); border-bottom: 12px solid var(--duckling-yellow); }

        /* Insight Cards */
        .insight-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin: 30px 0; }
        .insight-card { background: var(--white); padding: 30px; border: 1px solid #ddd; box-shadow: var(--shadow); position: relative; overflow: hidden; }
        .insight-card::before { content: ""; position: absolute; top: 0; left: 0; width: 5px; height: 100%; background: var(--bay-blue); }

        /* Question Section */
        .question-box { background: var(--bay-blue); color: white; padding: 40px; border-radius: 4px; margin: 20px 0; }
        .question-item { margin-bottom: 25px; font-size: 1.4rem; font-weight: bold; display: flex; align-items: flex-start; }
        .question-item span { color: var(--duckling-yellow); margin-right: 15px; font-size: 2rem; line-height: 1; }

        /* Tables */
        table { width: 100%; border-collapse: collapse; margin: 25px 0; background: white; }
        th { background: var(--bay-blue); color: white; padding: 18px; text-align: left; text-transform: uppercase; letter-spacing: 1px; }
        td { padding: 15px; border-bottom: 1px solid #ddd; font-size: 1.1rem; }
        tr:hover { background-color: #f9f9f9; }

        /* Roadmap Visualization */
        .roadmap { position: relative; padding: 20px 0; }
        .roadmap-step { display: flex; align-items: center; margin-bottom: 30px; }
        .step-number { background: var(--duckling-yellow); color: var(--bay-blue); width: 50px; height: 50px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold; font-size: 1.5rem; margin-right: 20px; flex-shrink: 0; }

        .fade-in { opacity: 0; transform: translateY(40px); transition: all 1.2s ease-out; }
        .fade-in.visible { opacity: 1; transform: translateY(0); }

        footer { background: #1a1a1a; color: white; padding: 60px 10%; text-align: center; }
    </style>
</head>
<body>

    <div id="progress-container"><div id="progress-bar"></div></div>

    <section class="hero-section">
        <div class="container">
            <p style="text-transform: uppercase; letter-spacing: 4px; font-weight: bold; color: var(--duckling-yellow); margin-bottom: 20px;">MPA Capstone Senior Leadership Briefing</p>
            <h1>Diagnosing and Modernizing <br>Public-Safety Hiring</h1>
            <p style="font-size: 2rem; opacity: 0.8; margin-top: 10px;">A Systems Approach to Workforce Stability</p>
            <div style="margin-top: 60px; font-size: 1.3rem; border-top: 1px solid rgba(255,255,255,0.3); padding-top: 30px;">
                <strong>Moses Zenon-Laguerre</strong><br>
                Recruiter & Program Coordinator III | Clark University
            </div>
        </div>
    </section>

    <section>
        <div class="container fade-in">
            <h2>The Yield Analysis</h2>
            <p style="font-size: 1.2rem; margin-bottom: 30px;">Our current pipeline is a "leaky funnel." We are successful at generating interest, but unsuccessful at maintaining momentum.</p>
            <table>
                <thead>
                    <tr>
                        <th>Metric Phase</th>
                        <th>Volume</th>
                        <th>Conversion</th>
                        <th>Systemic Resistance</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Initial Leads</td>
                        <td>2,000</td>
                        <td>100%</td>
                        <td>Marketing Success</td>
                    </tr>
                    <tr>
                        <td>Exam Registered</td>
                        <td>800</td>
                        <td>40%</td>
                        <td>High Friction / Wait Time</td>
                    </tr>
                    <tr>
                        <td>Academy Entry</td>
                        <td>150</td>
                        <td>7.5%</td>
                        <td>Systemic Attrition</td>
                    </tr>
                </tbody>
            </table>
            <p style="font-style: italic; color: var(--danger-red);">Finding: 92.5% of potential workforce lost to administrative latency.</p>
        </div>
    </section>

    <section style="background-color: var(--granite-gray);">
        <div class="container fade-in">
            <h2>The Dual-Loop Crisis</h2>
            <p style="margin-bottom: 40px;">The recruitment gap is caused by the collision of two opposing system velocities.</p>
            <div class="insight-grid">
                <div class="insight-card" style="border-top: 8px solid var(--berkshires-green);">
                    <h3 style="color: var(--berkshires-green);">The Fast Loop (Market)</h3>
                    <p style="margin-top:10px;">Digital ads, social media, and immediate engagement. Candidate expectation: <strong>Instant Feedback.</strong></p>
                </div>
                <div class="insight-card" style="border-top: 8px solid var(--bay-blue);">
                    <h3 style="color: var(--bay-blue);">The Slow Loop (Compliance)</h3>
                    <p style="margin-top:10px;">Civil service, background audits, and medical gates. System reality: <strong>10.2 Month Average.</strong></p>
                </div>
            </div>
            <div style="background: white; padding: 30px; border-radius: 8px; border: 1px solid #ccc;">
                <strong>The "Friction Zone":</strong> Candidates disengage at the 4-6 month mark, precisely when the Slow Loop is most silent.
            </div>
        </div>
    </section>

    <section>
        <div class="container fade-in">
            <h2>Modernization Roadmap</h2>
            <div class="roadmap">
                <div class="roadmap-step">
                    <div class="step-number">1</div>
                    <div>
                        <h3>Immediate Engagement (The 7-Day Pulse)</h3>
                        <p>Eliminate "Dead Time" by implementing automated, meaningful touchpoints every week of the process.</p>
                    </div>
                </div>
                <div class="roadmap-step">
                    <div class="step-number">2</div>
                    <div>
                        <h3>Parallel Processing</h3>
                        <p>Begin background investigations and medical clearances *prior* to final eligibility list publication to overlap wait times.</p>
                    </div>
                </div>
                <div class="roadmap-step">
                    <div class="step-number">3</div>
                    <div>
                        <h3>Evergreen Hiring Model</h3>
                        <p>Shift from "Cohort-Based" bursts to a continuous intake system to stabilize academy classes.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section style="background-color: var(--granite-gray);">
        <div class="container fade-in">
            <h2>Executive Conclusion</h2>
            <div class="insight-grid">
                <div class="insight-card">
                    <strong>Capacity vs. Interest</strong>
                    <p>Our staffing crisis is not a lack of interest, but a lack of system throughput capacity.</p>
                </div>
                <div class="insight-card">
                    <strong>Administrative Cost</strong>
                    <p>Silence is the most expensive part of our hiring process, leading to a 90%+ candidate loss.</p>
                </div>
            </div>

            <div class="question-box">
                <h3 style="color: var(--duckling-yellow); margin-bottom: 20px;">Strategic Questions for Leadership</h3>
                <div class="question-item">
                    <span>?</span> "Can we afford to maintain a 10-month hiring cycle in a 2-week job market?"
                </div>
                <div class="question-item">
                    <span>?</span> "Which administrative gates can be moved from 'Serial' to 'Parallel' processing?"
                </div>
                <div class="question-item">
                    <span>?</span> "How do we redefine 'Successful Outreach' to include 'Successful Retention'?"
                </div>
            </div>
        </div>
    </section>

    <section style="background-color: var(--bay-blue); color: white; text-align: center;">
        <div class="container fade-in">
            <h1 style="color: var(--duckling-yellow); font-size: 4.5rem;">"A system is what it does."</h1>
            <p style="font-size: 1.8rem; margin-top: 30px; opacity: 0.9;">To change the outcome, we must change the architecture.</p>
            <div style="margin-top: 100px;">
                <p style="font-weight: bold;">Moses Zenon-Laguerre</p>
                <p>Massachusetts Department of Correction | Clark University</p>
                <p>May 2026</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Strategic Modernization Report | Internal Presentation | RTC 339 Analysis</p>
    </footer>

    <script>
        // Progress Bar Logic
        window.onscroll = function() {
            let winScroll = document.body.scrollTop || document.documentElement.scrollTop;
            let height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
            let scrolled = (winScroll / height) * 100;
            document.getElementById("progress-bar").style.width = scrolled + "%";
        };

        // Scroll Reveal Logic
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
