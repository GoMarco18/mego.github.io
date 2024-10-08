
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Privacy and Cybercrime Reflection</title>
    <link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css">
    <script defer src="https://pyscript.net/latest/pyscript.js"></script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #2c3e50;
        }
        p, strong {
            color: #333;
            margin-bottom: 15px;
        }
        strong {
            color: #e74c3c;
        }
        #word-count {
            font-size: 1.2em;
            font-weight: bold;
            text-align: center;
            margin-top: 20px;
            color: #3498db;
        }
        blockquote {
            font-style: italic;
            color: #7f8c8d;
            margin: 20px 0;
            border-left: 3px solid #e74c3c;
            padding-left: 15px;
        }
    </style>
</head>
<body>
    <div id="word-count"></div>
    <div class="container" id="container"></div>

    <py-script>
        from js import document
        
        content = """
        <h1>Reflection on Data Privacy and Cybercrime</h1>
        <p>
            The presentation on the Data Privacy Act of 2012 (RA 10173) and cybercrime in the Philippines, led by <strong>PCOL JAY D GUILLERMO</strong>, Chief of the Cyber Response Unit of the Philippine National Police Anti-Cybercrime Group (PNP ACG), offered invaluable insights into the critical issues of data protection and the growing threats of cybercrime. The session shed light on the legal framework aimed at safeguarding personal information and emphasized the importance of cybersecurity in an increasingly digital world. As an IT student, the presentation gave me a clearer understanding of my future responsibilities in ensuring data security.
        <p>
            One of the key takeaways from the discussion was the emphasis on direct consent when collecting personal information. The Data Privacy Act mandates that organizations seek explicit approval from individuals before gathering their data. This legal requirement made me more aware of how often personal data is shared without much thought, especially through online platforms. As someone entering the IT industry, I now realize how crucial it will be to ensure that people are informed and in control of how their data is collected and used, reinforcing the importance of transparency and ethical data handling.
        </p>
        <p>
            Another significant point from the presentation was the issue of data security. While it’s easy for organizations to collect large amounts of data, keeping that information secure is a significant challenge. The law requires organizations to notify affected individuals and the National Privacy Commission (NPC) in case of a data breach. This brought into focus the real risks posed by cyber threats and the necessity of establishing strong security measures. For me, this was a clear reminder of how important cybersecurity will be in my future career. It’s not just about creating systems that function properly; it's about building robust systems that can withstand potential threats. 
        </p>
        <p>
            A particularly eye-opening moment during the presentation was the discussion on the handling of personal data after someone has passed away. I learned that the data of a deceased individual can still be accessed by their lawful heirs, which highlights the ongoing importance of data privacy, even after death. This made me realize that personal data is more than just information stored in databases—it represents a person’s life and identity, and it should be treated with care and respect at all stages.
        </p>
        <p>
           
        </p>
        <p>
          it also help me understand that there is more danger to ones who dont know than those who do and its my duty as a soon to be it profesional to help   
        </p>
        <blockquote>
            “Stay safe online: Protect your data, protect yourself and know your rights.”
        </blockquote>
        <p>
            Overall, the presentation helped me understand how data privacy and cybercrime affect everyone. It wasn’t just about laws and rules—it was about protecting people and making sure their personal information is safe. I enjoyed the event because it was both educational and fun, especially with the interactive parts and the prizes. <strong>PCOL JAY D GUILLERMO</strong>’s insights gave me a better understanding of my future responsibilities as an IT professional in the Philippines.
        </p>
        """
        
        # Insert content into the container
        container = document.getElementById("container")
        container.innerHTML = content
        
        # Calculate and display word count
        word_count = len(content.split())
        document.getElementById("word-count").innerHTML = f"Word Count: {word_count}"
    </py-script>
</body>
</html>
