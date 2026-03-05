<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Modern Mobile Styling with Red Accents */
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            margin: 0; 
            padding: 15px; 
            background-color: #f0f0f0; 
            color: #222;
        }
        .container { max-width: 600px; margin: auto; }

        /* Header matching your photo style */
        .header { 
            text-align: center; 
            background: #1a1a1a; 
            color: white; 
            padding: 40px 20px; 
            border-radius: 20px;
            border-bottom: 5px solid #ff0000; 
        }

        .profile-img { 
            width: 200px; 
            height: auto; 
            border-radius: 15px; 
            border: 3px solid #ff0000; 
            margin-top: 15px; 
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }

        .section { 
            background: white; 
            padding: 20px; 
            margin-top: 20px; 
            border-radius: 12px; 
            box-shadow: 0 2px 5px rgba(0,0,0,0.1); 
        }

        h2 { 
            color: #1a1a1a; 
            border-left: 5px solid #ff0000; 
            padding-left: 10px; 
        }

        /* Table styling for HND courses */
        .table-container { overflow-x: auto; }
        table { width: 100%; border-collapse: collapse; margin-top: 15px; font-size: 0.9rem; }
        th, td { border: 1px solid #ddd; padding: 12px; text-align: left; }
        th { background-color: #ff0000; color: white; }
        tr:nth-child(even) { background-color: #f9f9f9; }

        /* Contact & GitHub Button Styling */
        .btn {
            display: block;
            width: 100%;
            padding: 15px;
            margin-top: 10px;
            text-align: center;
            text-decoration: none;
            font-weight: bold;
            border-radius: 8px;
            box-sizing: border-box;
            color: white;
        }
        .whatsapp-btn { background-color: #25D366; }
        .github-btn { background-color: #333; } /* GitHub Black */
        .email-btn { background-color: #ff0000; }

        footer { text-align: center; margin-top: 30px; color: #777; font-size: 0.8rem; padding-bottom: 20px; }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Nafissatou Aboubakar</h1>
            <p>18 Years Old | HND Student | Programming Enthusiast</p>
            <img src="content://com.android.providers.media.documents/document/image%3A3554.jpg" alt="Nafissatou Aboubakar Photo" class="profile-img">
        </div>

        <div class="section">
            <h2>About Me</h2>
            <p>My name is <strong>Nafissatou Aboubakar</strong>. I am 18 years old and I <strong>love programming</strong>. I am currently pursuing my Higher National Diploma (HND) and am passionate about building software solutions.</p>
        </div>

        <div class="section">
            <h2>Courses & Lecturers</h2>
            <div class="table-container">
                <table>
                    <thead>
                        <tr><th>Course</th><th>Lecturer</th></tr>
                    </thead>
                    <tbody>
                        <tr><td>Analysis 1</td><td>Mr. Ngwafor Kelly</td></tr>
                        <tr><td>Computer Architecture</td><td>Mr. Che Kingsley</td></tr>
                        <tr><td>Web Programming</td><td>Mr. Yuven Carlson</td></tr>
                        <tr><td>Legal Regulation</td><td>Dr. Pada Valery</td></tr>
                        <tr><td>Probability & OS</td><td>Mr. Isofah</td></tr>
                        <tr><td>Maintenance & Methodology</td><td>Mr. Tanto</td></tr>
                        <tr><td>Software/Hardware Maintenance</td><td>Mr. Tanto</td></tr>
                        <tr><td>Structured Programming</td><td>Mr. Nguyap Elias</td></tr>
                        <tr><td>Computer Network</td><td>Mr. Timcha Elvis</td></tr>
                        <tr><td>Economics</td><td>Dr. Kumji</td></tr>
                    </tbody>
                </table>
            </div>
        </div>

        <div class="section">
            <h2>Connect with Me</h2>
            <p>Find my code and reach out for collaborations:</p>
            
            <a href="https://github.com/Nice-code-crypto" class="btn github-btn">View My Code on GitHub</a>
            
            <a href="https://wa.me/237687180362" class="btn whatsapp-btn">Message on WhatsApp</a>
            
            <a href="mailto:nafissatouaboubakarndaoyo@.com" class="btn email-btn">Email Me</a>
        </div>

        <footer>
            <p>&copy; 2026 Nafissatou Aboubakar | Built with Acode</p>
        </footer>
    </div>
</body>
</html>

