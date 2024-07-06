# json-resume
import json

resume_text = """
# (Insert the resume content here)
"""

def parse_resume(resume):
    # Implement the logic to parse the resume text and structure it into a dictionary
    resume_dict = {
        "name": "MANVI AGARWAL",
        "contact": {
            "phone": "+91-9084162522",
            "email": "ma0309@srmist.edu.in",
            "address": "Amroha, Uttar Pradesh, India - 244221"
        },
        "skills": ["c", "c++", "python", "html", "css", "sql", "communications", "team management", "creative", "data structures", "algorithms", "canva"],
        "summary": "I am a B.Tech computer science undergraduate and computer programmer...",
        "education": [
            {
                "institution": "SRM Institute of Science & Technology, Ghaziabad",
                "degree": "B.Tech. - Computer Science & Engineering",
                "years": "2021 - 2025",
                "cgpa": "9.25 / 10"
            },
            {
                "institution": "St. Mary's Convent Sr. Sec. School, Amroha",
                "degree": "12th | CBSE",
                "year": "2021",
                "percentage": "89 / 100"
            },
            {
                "institution": "St. Mary's Convent Sr. Sec. School, Amroha",
                "degree": "10th | CBSE",
                "year": "2019",
                "percentage": "85 / 100"
            }
        ],
        "internships": [
            {
                "company": "Pwc",
                "role": "IT / Computers - Software",
                "dates": "15 Feb, 2024 - Present",
                "description": "Cloud and Digital Analytics Launchpad program..."
            },
            {
                "company": "JP Morgan",
                "role": "IT / Computers - Software",
                "dates": "15 Jun, 2023 - 27 Oct, 2023",
                "description": "Software Engineering Virtual Experience..."
            }
        ],
        "projects": [
            {
                "name": "AADHAR CARD MASKING",
                "dates": "15 Oct, 2023 - 24 Jan, 2024",
                "description": "Aadhaar masking is a critical measure implemented to protect..."
            },
            {
                "name": "Payroll Management System",
                "dates": "19 Apr, 2023 - 12 Jul, 2023",
                "description": "The Payroll Management System contains the employees record..."
            },
            {
                "name": "Hostel Booking System",
                "dates": "05 Jan, 2023 - 17 Feb, 2023",
                "description": "The Hostel Booking System Project is a Console Based Application Written in C++..."
            }
        ],
        "certifications": [
            {
                "name": "Crash Course on Python",
                "date": "26 Oct, 2026",
                "score": "95 / 100",
                "skills": ["python"]
            },
            {
                "name": "Introduction to Artificial Intelligence (AI)",
                "date": "26 Oct, 2026",
                "score": "83.30 / 100",
                "skills": ["AI"]
            },
            {
                "name": "Introduction to Machine Learning on AWS",
                "date": "24 Oct, 2026",
                "score": "100 / 100",
                "skills": ["AWS"]
            },
            {
                "name": "Cloud Computing and distributed system",
                "date": "25 Mar, 2026",
                "score": "78 / 100",
                "skills": ["cloud computing"]
            },
            {
                "name": "DATABASE MANAGEMENT SYSTEM",
                "date": "25 Sep, 2025",
                "score": "65 / 100",
                "skills": ["DATABASE MANAGEMENT SYSTEM", "SQL"]
            }
        ],
        "workshops": [
            {
                "name": "Hands-on Cloud Computing with AWS",
                "date": "23 Mar, 2023",
                "institution": "devtoen",
                "description": "Completion of the 'Hands-On Cloud Computing with AWS Bootcamp'..."
            },
            {
                "name": "Tinder Clone using HTML and CSS",
                "date": "15 Feb, 2023",
                "institution": "devtown",
                "description": "It demonstrates my dedication to expanding my web development skills..."
            },
            {
                "name": "Backend Development using JavaScript, Node.js, and React.js",
                "date": "08 Feb, 2023",
                "institution": "devtown",
                "description": "It showcases my proficiency in creating robust, interactive, and responsive web applications..."
            },
            {
                "name": "Bootcamp on JavaScript and React JS",
                "date": "19 Jan, 2023",
                "institution": "devtown",
                "description": "It demonstrates my proficiency in creating modern, interactive, and responsive web applications..."
            },
            {
                "name": "Harry Potter Invisibility Cloak with Python and OpenCV",
                "date": "11 Jan, 2023",
                "institution": "devtown",
                "description": "It enhanced my innovative and technical abilities..."
            }
        ],
        "extra_curricular_activities": ["dance"],
        "personal_details": {
            "gender": "Female",
            "marital_status": "Single",
            "address": "Hno.69 Katra Gulam Ali, Amroha (J.P. Nagar), India, Amroha, Uttar Pradesh, India - 244221",
            "date_of_birth": "21 Sep, 2003",
            "languages_known": ["Hindi", "English"],
            "phone_numbers": ["+91-9084162522", "+91-9084162522"],
            "emails": ["ma0309@srmist.edu.in", "manviagarwal2109@gmail.com"]
        },
        "linkedin_profile": "https://www.linkedin.com/in/manvi-agarwal-580116227"
    }
    return resume_dict

parsed_resume = parse_resume(resume_text)

# Print the JSON formatted resume
print(json.dumps(parsed_resume, indent=4))
