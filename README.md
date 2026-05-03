
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
        #progress-bar { height: 6px; background: var(--duckling-yellow); width: 0%; }

        section {
            padding: 100px 10%;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            border-bottom: 1px solid #ddd;
        }

        .container { max-width: 1100px; margin: 0 auto; width: 100%; }

        h1 { font-size: 3.8rem; margin-bottom: 0.5rem; line-height: 1.1; color: var(--white); }
        h2 { color: var(--bay-blue); font-size: 2.5rem; margin-bottom: 20px; text-transform: uppercase; border-left: 10px solid var(--duckling-yellow); padding-left: 20px; }

        .hero-section { background-color: var(--bay-blue); color: var(--white); border-bottom: 10px solid var(--duckling-yellow); }

        /* New Component: Dual-Loop Visualizer */
        .loop-container {
            display: flex;
            gap: 20px;
            margin: 40px 0;
        }
        .loop-card {
            flex: 1;
            padding: 30px;
            border-radius: 8px;
            color: white;
        }
        .fast-loop { background: var(--berkshires-green); }
        .slow-loop { background: var(--bay-blue); }

        /* Table Styles for Data Deep-Dive */
        table { width: 100%; border-collapse: collapse; margin: 25px 0; font-size: 1.1rem; }
        th { background: var(--bay-blue); color: white; padding: 15px; text-align: left; }
        td { padding: 12px; border-bottom: 1px solid #ddd; }
        tr:nth-child(even) { background: var(--granite-gray); }

        .highlight-box { background: #fff3cd; border-left: 5px solid #ffeeba; padding: 20px; margin: 20px 0; }

        .fade-in { opacity: 0; transform: translateY(30px); transition: all 1s ease-out; }
        .fade-in.visible { opacity: 1; transform: translateY(0); }

        footer { background: #222; color: white; padding: 60px 10%; text-align: center; }
    </style>
</head>
<body>

    <div id="progress-container"><div id="progress-bar"></div></div>

    <section class="hero-section">
        <div class="container">
            <p style="text-transform: uppercase; letter-spacing: 3px; font-weight: bold; color: var(--duckling-yellow);">Senior Leadership Briefing</p>
            <h1>Diagnosing and Modernizing Public-Safety Hiring</h1>
            <p style="font-size: 1.8rem; opacity: 0.9;">A Systems Performance Audit & Strategic Roadmap</p>
            <div style="margin-top: 40px; font-size: 1.2rem; border-top: 1px solid rgba(255,255,255,0.2); padding-top: 20px;">
                <strong>Moses Zenon-Laguerre</strong><br>
                MPA Capstone | Department of Correction
            </div>
        </div>
    </section>

    <section>
        <div class="container fade-in">
            <h2>The Dual-Loop Crisis</h2>
            <p>Recruitment fails because we are operating two systems that move at incompatible speeds.</p>
            
            <div class="loop-container">
                <div class="loop-card fast-loop">
                    <h3>The Fast Loop (Outreach)</h3>
                    <p>High-frequency digital engagement. Candidate response time: <strong>Minutes/Hours</strong>.</p>
                    <ul style="margin-top:15px; padding-left:20px;">
                        <li>Social Media Ads</li>
                        <li>Lead Collection</li>
                        <li>Job Fairs</li>
                    </ul>
                </div>
                <div class="loop-card slow-loop">
                    <h3>The Slow Loop (Compliance)</h3>
                    <p>Structural administrative gates. Candidate response time: <strong>Months</strong>.</p>
                    <ul style="margin-top:15px; padding-left:20px;">
                        <li>Civil Service Exams</li>
                        <li>Background Audits</li>
                        <li>Medical/Psych Clearances</li>
                    </ul>
                </div>
            </div>
            <div class="highlight-box">
                <strong>The Result:</strong> The "Friction" created by the Slow Loop causes 50% of Fast Loop leads to disengage within 120 days.
            </div>
        </div>
    </section>

    <section style="background: var(--granite-gray);">
        <div class="container fade-in">
            <h2>Audit: RTC 339 Pipeline</h2>
            <p>Analysis of 2,000 candidate touchpoints reveals the specific points of systemic failure.</p>
            
            <table>
                <thead>
                    <tr>
                        <th>Stage</th>
                        <th>Candidate Count</th>
                        <th>% of Original Pool</th>
                        <th>Status</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Initial Database Leads</td>
                        <td>2,000</td>
                        <td>100%</td>
                        <td>Peak Interest</td>
                    </tr>
                    <tr>
                        <td>Exam Registration</td>
                        <td>800</td>
                        <td>40%</td>
                        <td>Initial Friction</td>
                    </tr>
                    <tr>
                        <td>Eligible Roster</td>
                        <td>600</td>
                        <td>30%</td>
                        <td>Admin Latency</td>
                    </tr>
                    <tr>
                        <td>Academy Entry</td>
                        <td>150</td>
                        <td>7.5%</td>
                        <td>Final Yield</td>
                    </tr>
                </tbody>
            </table>
            <p style="color: var(--danger-red); font-weight: bold;">*Total Pipeline Loss: 92.5%</p>
        </div>
    </section>

    <section>
        <div class="container fade-in">
            <h2>Strategic Solutions</h2>
            <p>We don't need more leads; we need a better <strong>System Throughput</strong>.</p>
            
            <div style="display:grid; grid-template-columns: 1fr 1fr; gap: 30px; margin-top: 30px;">
                <div style="border: 1px solid #ccc; padding: 25px;">
                    <h3 style="color: var(--bay-blue);">1. Latency Compression</h3>
                    <p>Enforce a "7-Day Pulse." If the system is silent for 7 days, an automated engagement is triggered to maintain psychological momentum.</p>
                </div>
                <div style="border: 1px solid #ccc; padding: 25px;">
                    <h3 style="color: var(--bay-blue);">2. Parallel Processing</h3>
                    <p>Moving background investigations <em>forward</em> in the timeline to overlap with Civil Service wait times.</p>
                </div>
            </div>
        </div>
    </section>

    <section style="background-color: var(--bay-blue); color: white;">
        <div class="container fade-in">
            <h2 style="color: var(--duckling-yellow); border-left-color: var(--white);">Implementation Roadmap</h2>
            <div style="margin-top: 40px;">
                <div style="margin-bottom: 20px;">
                    <strong>Phase 1 (Months 1-3):</strong> Audit and automate the "Dead Time" touchpoints.
                </div>
                <div style="margin-bottom: 20px;">
                    <strong>Phase 2 (Months 3-6):</strong> Synchronize Recruitment and Background Investigation units.
                </div>
                <div style="margin-bottom: 20px;">
                    <strong>Phase 3 (Months 6+):</strong> Transition to a Year-Round "Evergreen" Hiring Model.
                </div>
            </div>
            <p style="font-size: 1.5rem; margin-top: 40px; text-align: center; font-style: italic;">
                "The system fails not because candidates are missing, but because our process is designed for a world that no longer waits."
            </p>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Moses Zenon-Laguerre | Clark University MPA Capstone</p>
    </footer>

    <script>
        window.onscroll = function() {
            let winScroll = document.body.scrollTop || document.documentElement.scrollTop;
            let height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
            let scrolled = (winScroll / height) * 100;
            document.getElementById("progress-bar").style.width = scrolled + "%";
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) entry.target.classList.add('visible');
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
    </script>
</body>
</html>
