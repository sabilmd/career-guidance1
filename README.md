<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One-Stop Personalized career And Education Adviser</title>

        <script src="https://cdn.tailwindcss.com"></script>
    
        <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    
        <script src="https://unpkg.com/lucide@latest"></script>

        <link rel="stylesheet" href="style.css">

</head>
<body>
     <div class="container mx-auto max-w-7xl min-h-screen flex flex-col">

        <header class="bg-white shadow-sm sticky top-0 z-10">
            <nav class="flex items-center justify-between p-4">
                <div class="flex items-center space-x-2">
                    <i data-lucide="compass" class="text-blue-600"></i>
                    <h1 class="text-2xl font-bold text-gray-800">Career Guide J&K</h1>
                </div>
                <button id="mobile-menu-button" class="md:hidden">
                    <i data-lucide="menu"></i>
                </button>
                <div class="hidden md:flex items-center space-x-6">
                    <a href="#" class="nav-link text-gray-600 hover:text-blue-600 font-medium" data-view="dashboard">Dashboard</a>
                    <a href="#" class="nav-link text-gray-600 hover:text-blue-600 font-medium" data-view="aptitude-test">Aptitude Test</a>
                    <a href="#" class="nav-link text-gray-600 hover:text-blue-600 font-medium" data-view="career-paths">Career Paths</a>
                    <a href="#" class="nav-link text-gray-600 hover:text-blue-600 font-medium" data-view="colleges">Find Colleges</a>
                    <a href="#" class="nav-link text-gray-600 hover:text-blue-600 font-medium" data-view="timeline">Timeline</a>
                    <a href="#" class="nav-link text-gray-600 hover:text-blue-600 font-medium" data-view="resources">Resources</a>
                </div>
            </nav>
            <div id="mobile-menu" class="hidden md:hidden bg-white p-4">
                 <a href="#" class="nav-link block py-2 text-gray-600 hover:text-blue-600" data-view="dashboard">Dashboard</a>
                 <a href="#" class="nav-link block py-2 text-gray-600 hover:text-blue-600" data-view="aptitude-test">Aptitude Test</a>
                 <a href="#" class="nav-link block py-2 text-gray-600 hover:text-blue-600" data-view="career-paths">Career Paths</a>
                 <a href="#" class="nav-link block py-2 text-gray-600 hover:text-blue-600" data-view="colleges">Find Colleges</a>
                 <a href="#" class="nav-link block py-2 text-gray-600 hover:text-blue-600" data-view="timeline">Timeline</a>
                 <a href="#" class="nav-link block py-2 text-gray-600 hover:text-blue-600" data-view="resources">Resources</a>
            </div>
        </header>

        <main class="flex-grow p-4 md:p-8">

            <div id="dashboard" class="view active">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Welcome, Student!</h2>
                    <p class="text-gray-600 mt-2 text-lg">Your one-stop platform for career clarity in Jammu & Kashmir.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-8">
                    <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow cursor-pointer nav-link" data-view="aptitude-test"><div class="flex items-center space-x-4"><div class="bg-blue-100 p-3 rounded-full"><i data-lucide="lightbulb" class="text-blue-600"></i></div><div><h3 class="text-xl font-semibold text-gray-800">Discover Your Path</h3><p class="text-gray-500">Take our short aptitude test to find the best stream for you.</p></div></div></div>
                    <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow cursor-pointer nav-link" data-view="career-paths"><div class="flex items-center space-x-4"><div class="bg-green-100 p-3 rounded-full"><i data-lucide="map" class="text-green-600"></i></div><div><h3 class="text-xl font-semibold text-gray-800">Explore Careers</h3><p class="text-gray-500">Visually map your course to future jobs and higher studies.</p></div></div></div>
                    <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow cursor-pointer nav-link" data-view="colleges"><div class="flex items-center space-x-4"><div class="bg-purple-100 p-3 rounded-full"><i data-lucide="school" class="text-purple-600"></i></div><div><h3 class="text-xl font-semibold text-gray-800">Find Govt. Colleges</h3><p class="text-gray-500">Search for colleges in J&K and see what they offer.</p></div></div></div>
                    <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow cursor-pointer nav-link" data-view="timeline"><div class="flex items-center space-x-4"><div class="bg-yellow-100 p-3 rounded-full"><i data-lucide="calendar-days" class="text-yellow-600"></i></div><div><h3 class="text-xl font-semibold text-gray-800">Important Dates</h3><p class="text-gray-500">Track admission deadlines and scholarship dates.</p></div></div></div>
                    <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow cursor-pointer nav-link" data-view="resources"><div class="flex items-center space-x-4"><div class="bg-red-100 p-3 rounded-full"><i data-lucide="book-open" class="text-red-600"></i></div><div><h3 class="text-xl font-semibold text-gray-800">Student Resources</h3><p class="text-gray-500">Access study materials, e-books, and scholarship info.</p></div></div></div>
                    <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow cursor-pointer nav-link" data-view="aptitude-test"><div class="flex items-center space-x-4"><div class="bg-indigo-100 p-3 rounded-full"><i data-lucide="user-check" class="text-indigo-600"></i></div><div><h3 class="text-xl font-semibold text-gray-800">Personalized Suggestions</h3><p class="text-gray-500">AI-driven recommendations for courses and colleges (Coming Soon!).</p></div></div></div>
                </div>

                <div class="mt-16 bg-white p-8 rounded-lg shadow-md">
                    <h2 class="text-2xl font-bold text-center text-gray-800 mb-4">About Our Platform</h2>
                    <p class="text-gray-600 leading-relaxed mb-6 text-center max-w-3xl mx-auto">
                        Career Guide is a comprehensive digital platform designed to empower students in making informed decisions about their future. We understand that choosing a career path is one of the most critical steps in a student's life. Our mission is to provide clear, accessible, and reliable guidance, bridging the gap between education and employment.
                    </p>
                    <div class="border-t pt-6">
                        <h3 class="text-xl font-semibold text-center text-gray-800 mb-4">What We Offer</h3>
                        <ul class="space-y-3 text-gray-600 list-disc list-inside max-w-2xl mx-auto">
                            <li>
                                <strong>Aptitude Testing:</strong> Discover your strengths and interests with our tailored quiz to find the best academic stream for you.
                            </li>
                            <li>
                                <strong>Detailed Career Paths:</strong> Explore a vast database of career options after the 10th and 12th grades, with detailed information on eligibility, entrance exams, top colleges, and future prospects.
                            </li>
                            <li>
                                <strong>College Directory:</strong> Find and compare government colleges, complete with details on offered programs and facilities.
                            </li>
                            <li>
                                <strong>Important Timeline:</strong> Never miss a deadline with our curated timeline of admission dates, scholarship applications, and entrance tests.
                            </li>
                            <li>
                                <strong>Student Resources:</strong> Access a collection of helpful links for study materials, e-books, and scholarship portals.
                            </li>
                            <li>
                              <strong>Carrer Guider:</strong> An AI-powered career guidance assistant that helps students and professionals choose the right path, explore opportunities, and make smarter career decisions.
                                </li>
                        </ul>
                    </div>
                </div>
                </div>

            <div id="aptitude-test" class="view"><div id="quiz-container" class="max-w-2xl mx-auto bg-white p-8 rounded-lg shadow-lg"></div><div id="quiz-result" class="hidden max-w-2xl mx-auto bg-white p-8 rounded-lg shadow-lg text-center"><h3 class="text-2xl font-bold mb-4">Test Complete!</h3><p class="text-lg mb-2">Based on your answers, we recommend you explore:</p><div id="recommendation" class="text-3xl font-bold text-blue-600 my-4 p-4 bg-blue-50 rounded-lg"></div><p class="text-gray-600 mb-6">This is a suggestion to guide your exploration. Your interests are unique!</p><button id="explore-recommendation-btn" class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700 transition-colors">Explore Career Paths</button></div></div>

            <div id="career-paths" class="view"><h2 class="text-3xl font-bold text-center mb-8">Course-to-Career Path Mapping</h2><div id="career-choice-container" class="max-w-3xl mx-auto text-center"></div><div id="career-path-content" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mt-8"></div></div>

            <div id="colleges" class="view"><h2 class="text-3xl font-bold text-center mb-8">Nearby Government Colleges Directory</h2><div class="max-w-3xl mx-auto mb-6"><input type="text" id="college-search" placeholder="Search by college name or city..." class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:outline-none"></div><div id="college-list" class="space-y-4"></div></div>

            <div id="timeline" class="view"><h2 class="text-3xl font-bold text-center mb-8">Timeline & Notifications</h2><div id="timeline-list" class="max-w-3xl mx-auto bg-white p-6 rounded-lg shadow-md"></div></div>

            <div id="resources" class="view">
                <h2 class="text-3xl font-bold text-center mb-8">Student Resources</h2>
                <div id="resources-content" class="max-w-4xl mx-auto space-y-8"></div>
            </div>

        </main>

        <footer class="text-center p-4 bg-white mt-8 border-t">
            <p class="text-gray-500">Created By Cool Coders</p>
        </footer>
    </div>

    <script src="script.js" defer></script>
    
    <script type="text/javascript">
      (function(d, t) {
          var v = d.createElement(t), s = d.getElementsByTagName(t)[0];
          v.onload = function() {
            window.voiceflow.chat.load({
              verify: { projectID: '68c422782162423ad1f7c194' },
              url: 'https://general-runtime.voiceflow.com',
              versionID: 'production',
              voice: {
                url: "https://runtime-api.voiceflow.com"
              }
            });
          }
          v.src = "https://cdn.voiceflow.com/widget-next/bundle.mjs"; v.type = "text/javascript"; s.parentNode.insertBefore(v, s);
      })(document, 'script');
    </script>
    
</body>
</html>


document.addEventListener('DOMContentLoaded', () => {

    // --- MOCK DATA ---
    const quizQuestions = [{ question: "Which subject do you enjoy the most in school?", options: [{ text: "Physics or Biology", stream: "science" }, { text: "History or Literature", stream: "arts" }, { text: "Economics or Business Studies", stream: "commerce" }] }, { question: "What kind of activity would you prefer for a project?", options: [{ text: "Conducting a scientific experiment", stream: "science" }, { text: "Writing a creative story or a historical report", stream: "arts" }, { text: "Creating a business plan for a new product", stream: "commerce" }] }, { question: "When you read the news, what section are you most drawn to?", options: [{ text: "Technology and Environment", stream: "science" }, { text: "Culture, Society, and Politics", stream: "arts" }, { text: "Business and the Stock Market", stream: "commerce" }] }, { question: "Which career sounds most appealing to you?", options: [{ text: "Doctor, Engineer, or Researcher", stream: "science" }, { text: "Journalist, Lawyer, or Social Worker", stream: "arts" }, { text: "Chartered Accountant, Marketing Manager, or Entrepreneur", stream: "commerce" }] }, { question: "How do you prefer to solve problems?", options: [{ text: "With logic, data, and experimentation", stream: "science" }, { text: "By understanding different perspectives and human behavior", stream: "arts" }, { text: "By analyzing costs, benefits, and market trends", stream: "commerce" }] }, { question: "What kind of books do you enjoy reading in your free time?", options: [{ text: "Science fiction or books about scientific discoveries", stream: "science" }, { text: "Classic novels, poetry, or historical biographies", stream: "arts" }, { text: "Books on finance, business success, or economics", stream: "commerce" }] }, { question: "What genre of movies or TV shows do you prefer?", options: [{ text: "Nature/space documentaries or sci-fi thrillers", stream: "science" }, { text: "Thought-provoking dramas or historical epics", stream: "arts" }, { text: "Shows like Shark Tank or movies about the business world", stream: "commerce" }] }, { question: "When faced with a complex topic, you first try to...", options: [{ text: "Break it down into logical, testable parts", stream: "science" }, { text: "Understand its cultural and historical context", stream: "arts" }, { text: "Assess its practical applications and potential value", stream: "commerce" }] }, { question: "In a group project, what role do you naturally take on?", options: [{ text: "The researcher or technical expert who handles data", stream: "science" }, { text: "The writer or presenter who crafts the main story", stream: "arts" }, { text: "The project manager who organizes tasks and resources", stream: "commerce" }] }, { question: "What kind of impact do you want to make in your career?", options: [{ text: "Discover something new or build innovative technology", stream: "science" }, { text: "Inspire people through creativity or advocate for social change", stream: "arts" }, { text: "Create a successful business or manage large-scale operations", stream: "commerce" }] }, { question: "Which type of puzzle do you find more engaging?", options: [{ text: "A logical puzzle with a single correct answer, like Sudoku", stream: "science" }, { text: "An interpretive puzzle with many meanings, like analyzing art", stream: "arts" }, { text: "A strategic puzzle about managing resources, like chess", stream: "commerce" }] }, { question: "Which set of tools would you rather work with?", options: [{ text: "A microscope, a telescope, or coding software", stream: "science" }, { text: "A camera, a paintbrush, or a writer's journal", stream: "arts" }, { text: "A spreadsheet, a financial calculator, or a business plan", stream: "commerce" }] }, { question: "You learn a new skill best by...", options: [{ text: "Doing hands-on experiments and seeing the results", stream: "science" }, { text: "Reading, discussing, and debating the core ideas", stream: "arts" }, { text: "Analyzing real-world case studies and examples", stream: "commerce" }] }, { question: "Your ideal workspace would be...", options: [{ text: "A clean, organized lab or a quiet space for deep focus", stream: "science" }, { text: "A creative studio, a library, or out in the field", stream: "arts" }, { text: "A busy, collaborative office or a boardroom", stream: "commerce" }] }, { question: "Which statement best describes you?", options: [{ text: "I am curious about how things work.", stream: "science" }, { text: "I am curious about why people do the things they do.", stream: "arts" }, { text: "I am curious about how systems and organizations function.", stream: "commerce" }] }];
    const careerDataAfter10th = { science: { title: 'Science Stream (11th-12th)', icon: 'atom', color: 'blue', description: 'Ideal for students interested in scientific theory, experimentation, and technology. Opens doors to Engineering, Medicine, and Research.', options: ['Key Subjects: Physics, Chemistry, Maths (PCM)', 'Also available with Biology (PCB) for medical fields.'] }, commerce: { title: 'Commerce Stream (11th-12th)', icon: 'landmark', color: 'purple', description: 'Perfect for those interested in business, finance, and economics. Leads to careers like CA, banking, and management.', options: ['Key Subjects: Accountancy, Business Studies, Economics.'] }, arts: { title: 'Arts / Humanities (11th-12th)', icon: 'scroll-text', color: 'green', description: 'Explores human society, culture, and history. Suited for creative minds and future civil servants, lawyers, or journalists.', options: ['Key Subjects: History, Political Science, Literature.'] }, polytechnic: { title: 'Polytechnic / Diploma', icon: 'wrench', color: 'orange', description: 'Offers 3-year diploma courses in technical fields like Civil, Mechanical, or Computer Engineering for hands-on skills.', options: ['Benefit: Allows direct entry into the 2nd year of a B.Tech degree.'] }, iti: { title: 'ITI (Vocational Training)', icon: 'hammer', color: 'red', description: 'Provides short-term (1-2 years) job-oriented training in specific trades like electrician, fitter, or computer operator.', options: ['Benefit: Quick employment opportunities in skilled trades.'] }, paramedical: { title: 'Paramedical Courses', icon: 'syringe', color: 'teal', description: 'Focuses on healthcare sector roles. Courses like Diploma in Medical Laboratory Technology (DMLT) can be pursued.', options: ['Benefit: Entry into the allied healthcare services field.'] } };
    const careerDataAfter12th = {
        engineeringCse: {
            title: 'Computer Science Engineering',
            icon: 'cpu',
            color: 'blue',
            description: 'Focuses on the design, development, and maintenance of software systems, AI, cybersecurity, and data science.',
            eligibility: '10+2 with Physics, Chemistry, and Mathematics (PCM).',
            entranceExams: ['JEE Main', 'MHT-CET', 'BITSAT', 'State-level CETs'],
            topCareers: ['Software Developer', 'AI/ML Engineer', 'Data Scientist', 'Cybersecurity Analyst', 'Cloud Engineer'],
            avgSalary: '₹7–20 LPA (Data Scientist)',
            topColleges: ['K. J. Somaiya Institute of Engineering, Mumbai', 'Mukesh Patel School of Technology, Mumbai', 'MIT-WPU, Pune', 'Dr. D. Y. Patil Institute of Technology, Pune'],
            higherEducation: ['M.Tech in Specializations', 'MS from foreign universities', 'MBA']
        },
        computerApplications: {
            title: "Computer Applications (BCA)",
            icon: 'laptop-2',
            color: 'violet',
            description: "A 3-year degree providing a foundational understanding of computer applications and software development, open to students from any stream.",
            eligibility: "10+2 from any stream (Maths often required), with 45–50% aggregate.",
            entranceExams: ['MAH BCA CET', 'CUET UG', 'SET'],
            topCareers: ['Software Developer', 'Web Developer', 'Data Analyst', 'Cybersecurity Analyst', 'System Analyst'],
            avgSalary: "₹5–12 LPA (Software Developer)",
            topColleges: ['Symbiosis (SICSR), Pune', 'MIT-WPU, Pune', 'BMCC, Pune', 'K.P.B. Hinduja College, Mumbai'],
            higherEducation: ['Master of Computer Applications (MCA)', 'MBA', 'Specialized Certifications']
        },
        engineeringAero: {
            title: "Aeronautical Engineering",
            icon: 'plane-takeoff',
            color: 'cyan',
            description: "A specialized field focused on the design, development, and testing of aircraft like airplanes, helicopters, and drones.",
            eligibility: "10+2 with Physics, Chemistry, and Mathematics (PCM).",
            entranceExams: ['JEE Main', 'GATE (for M.Tech)'],
            topCareers: ['Aircraft Design Engineer', 'Propulsion Engineer', 'Avionics Engineer', 'Flight Test Engineer', 'UAV Engineer'],
            avgSalary: "₹5–7 LPA (Entry-level)",
            topColleges: ['IIT Bombay', 'IIT Madras', 'Indian Institute of Space Science and Technology (IIST)', 'Punjab Engineering College'],
            higherEducation: ['M.Tech/M.E.', 'Ph.D.']
        },
        engineeringCivil: {
            title: "Civil Engineering",
            icon: 'hard-hat',
            color: 'slate',
            description: "Focuses on designing, constructing, and maintaining the infrastructure of society, such as buildings, bridges, and water systems.",
            eligibility: "10+2 with Physics, Chemistry, and Mathematics (PCM).",
            entranceExams: ['JEE Main', 'MHT-CET', 'State-level CETs'],
            topCareers: ['Structural Engineer', 'Transportation Engineer', 'Environmental Engineer', 'Construction Manager', 'Urban Planner'],
            avgSalary: "₹4–9 LPA (Varies by role)",
            topColleges: ['IIT Bombay', 'Veermata Jijabai Technological Institute (VJTI), Mumbai', 'College of Engineering, Pune (COEP)'],
            higherEducation: ['M.Tech (Structural, Environmental)', 'MBA in Construction Management']
        },
        architecture: {
            title: "Bachelor of Architecture (B.Arch)",
            icon: 'drafting-compass',
            color: 'lime',
            description: "A five-year program focusing on the art and science of designing and constructing buildings. A license from the Council of Architecture is required to practice.",
            eligibility: "10+2 with Physics, Chemistry, and Mathematics (PCM).",
            entranceExams: ['NATA', 'JEE Main Paper 2', 'JEE Advanced (AAT) for IITs'],
            topCareers: ['Architectural Designer', 'Project Manager', 'Landscape Architect', 'Urban Planner', 'Interior Designer'],
            avgSalary: "₹7 LPA (Architectural Designer)",
            topColleges: ['Sir J.J. College of Architecture, Mumbai', 'IIT Kharagpur/Roorkee', 'School of Planning and Architecture (SPA), Delhi', 'CEPT University, Ahmedabad'],
            higherEducation: ['Master of Architecture (M.Arch)', 'MBA in Construction Management']
        },
        medicalMbbsBds: {
            title: 'Doctor / Dentist (MBBS/BDS)',
            icon: 'stethoscope',
            color: 'red',
            description: 'MBBS is a 5.5-year degree to become a medical doctor, while BDS is a 5-year degree to become a dental surgeon.',
            eligibility: '10+2 with Physics, Chemistry, Biology (PCB) and a minimum of 50% aggregate marks (40% for reserved).',
            entranceExams: ['NEET-UG (mandatory for all colleges)'],
            topCareers: ['General Practitioner', 'Specialist Surgeon (after MD/MS)', 'General Dentist', 'Orthodontist (after MDS)', 'Medical Officer'],
            avgSalary: 'Varies widely based on specialization and practice.',
            topColleges: ['AFMC, Pune', 'Grant Medical College, Mumbai', 'B. J. Government Medical College, Pune', 'Topiwala National Medical College, Mumbai'],
            higherEducation: ['MD/MS (after MBBS)', 'MDS (after BDS)']
        },
        law: {
            title: 'Law (B.A. LLB)',
            icon: 'scale',
            color: 'indigo',
            description: 'A five-year integrated program that combines Arts and Social Science studies with a comprehensive legal education.',
            eligibility: '10+2 from any stream with a minimum of 45-50% aggregate marks.',
            entranceExams: ['CLAT', 'MHCET Law', 'University-specific exams'],
            topCareers: ['Litigation Lawyer', 'Corporate Lawyer', 'Judge', 'Legal Advisor', 'Public Prosecutor'],
            avgSalary: '₹6–12 LPA (Corporate Lawyer)',
            topColleges: ['Government Law College (GLC), Mumbai', 'ILS Law College, Pune', 'Symbiosis Law School (SLS), Pune', "SVKM's PGCL, Mumbai"],
            higherEducation: ['Master of Laws (LLM)', 'MBA', 'PhD in Law']
        },
        designBdes: {
            title: "Bachelor of Design (B.Des)",
            icon: 'pencil-ruler',
            color: 'fuchsia',
            description: "A four-year program for students interested in creative problem-solving, integrating theory with hands-on skills for the creative industry.",
            eligibility: "10+2 from any stream with 45–50% aggregate.",
            entranceExams: ['MAH B.Design CET', 'UCEED', 'NIFT Entrance Exam'],
            topCareers: ['UI/UX Designer', 'Graphic Designer', 'Product Designer', 'Fashion Designer', 'Animator'],
            avgSalary: "₹3–8 LPA (Entry-level)",
            topColleges: ['IIT Bombay (IDC)', 'Symbiosis Institute of Design, Pune', 'MITID, Pune', 'NIFT, Mumbai'],
            higherEducation: ['Master of Design (M.Des)']
        },
        artsBfa: {
            title: "Bachelor of Fine Arts (BFA)",
            icon: 'palette',
            color: 'rose',
            description: "A four-year degree focusing heavily on practical, hands-on artistic training for a professional career in visual or performing arts.",
            eligibility: "10+2 from any stream with a minimum of 50% aggregate.",
            entranceExams: ['MAH-AAC-CET', 'Portfolio Review & Interview'],
            topCareers: ['Graphic Designer', 'Animator/VFX Artist', 'Illustrator', 'Art Director', 'Fine Artist'],
            avgSalary: "₹3–6 LPA (Entry-level)",
            topColleges: ['Sir J.J. Institute of Applied Art, Mumbai', 'MIT-WPU, Pune', 'K.K. Wagh College of Fine Arts, Nashik'],
            higherEducation: ['Master of Fine Arts (MFA)', 'Master of Design (M.Des)']
        },
        journalism: {
            title: "Journalism (BJMC)",
            icon: 'newspaper',
            color: 'amber',
            description: "A three-year program training students in media, communication, and journalism for print, broadcast, and digital platforms.",
            eligibility: "10+2 from any stream with 45–50% aggregate.",
            entranceExams: ['CUET', 'Symbiosis SET', 'University-specific exams'],
            topCareers: ['Journalist/Reporter', 'Public Relations (PR) Specialist', 'Content Creator', 'Social Media Manager'],
            avgSalary: "₹3–6 LPA (Entry-level)",
            topColleges: ['Symbiosis Institute of Media & Communication, Pune', 'Xavier Institute of Communications, Mumbai', 'MIT-WPU, Pune'],
            higherEducation: ['Master of Arts (MA) in Journalism', 'MBA in Media Management']
        },
        managementHotel: {
            title: 'Hotel Management',
            icon: 'building',
            color: 'teal',
            description: 'A professional field focused on overseeing all operations within a hotel, including front office, food and beverage, and marketing.',
            eligibility: '10+2 from any stream.',
            entranceExams: ['NCHMCT JEE (for IHMs)', 'College-specific entrance exams.'],
            topCareers: ['Hotel Manager', 'Executive Chef', 'Event Manager', 'Cruise Line Manager', 'Airline Catering Manager'],
            avgSalary: '₹3.5–6 LPA (with 3-5 years experience)',
            topColleges: ['IHM, Mumbai', 'AISSMS College of HMCT, Pune', 'MSIHMCT, Pune', 'ITM Institute of Hotel Management, Navi Mumbai'],
            higherEducation: ['MBA in Hospitality Management', 'Master of Hotel Management (MHM)']
        }
    };
    const collegeData = [{ name: 'Amar Singh College', city: 'Srinagar', courses: ['B.A.', 'B.Sc.', 'B.Com', 'BCA'], facilities: ['Library', 'Hostel', 'Computer Lab'] }, { name: 'Sri Pratap (SP) College', city: 'Srinagar', courses: ['B.Sc. (Medical/Non-Medical)', 'BCA', 'B.Sc. IT'], facilities: ['Library', 'Labs', 'Hostel', 'Internet'] }, { name: 'Govt. College for Women, M.A. Road', city: 'Srinagar', courses: ['B.A.', 'B.Sc.', 'B.Com', 'Home Science'], facilities: ['Library', 'Hostel', 'Canteen'] }, { name: 'Islamia College of Science and Commerce', city: 'Srinagar', courses: ['B.Sc', 'B.Com', 'BBA', 'BCA'], facilities: ['Library', 'Auditorium', 'Labs'] }, { name: 'Government Degree College for Boys, Anantnag', city: 'Anantnag', courses: ['B.A.', 'B.Sc.', 'B.Com', 'BCA'], facilities: ['Library', 'Reading Room', 'Sports'] }, { name: 'Government Degree College for Boys, Baramulla', city: 'Baramulla', courses: ['B.A.', 'B.Sc.', 'B.Com', 'BBA'], facilities: ['Library', 'Computer Lab', 'Gym'] }, { name: 'Govt. Gandhi Memorial (GGM) Science College', city: 'Jammu', courses: ['B.Sc.', 'BCA', 'Geology', 'Electronics'], facilities: ['Hostel', 'Library', 'Advanced Labs'] }, { name: 'Govt. College for Women, Parade Ground', city: 'Jammu', courses: ['B.A.', 'B.Sc.', 'B.Com', 'BCA'], facilities: ['Library', 'Hostel', 'Computer Lab'] }, { name: 'SPMR College of Commerce', city: 'Jammu', courses: ['B.Com (General)', 'BBA', 'BCA'], facilities: ['Library', 'Smart Classrooms', 'Auditorium'] }, { name: 'Government Degree College, Kathua', city: 'Kathua', courses: ['B.A.', 'B.Sc.', 'B.Com', 'BCA'], facilities: ['Library', 'NSS', 'NCC', 'Labs'] }, { name: 'Government Degree College, Udhampur', city: 'Udhampur', courses: ['B.A.', 'B.Sc.', 'B.Com', 'BCA'], facilities: ['Library', 'Computer Lab', 'Canteen'] }, { name: 'Government Degree College, Poonch', city: 'Poonch', courses: ['B.A.', 'B.Sc.', 'B.Com'], facilities: ['Library', 'Internet', 'Labs'] }, { name: 'Government Degree College, Sopore', city: 'Sopore', courses: ['B.A.', 'B.Sc.', 'B.Com'], facilities: ['Library', 'Sports', 'Computer Lab'] }];
    const timelineData = [{ date: '2025-09-28', title: 'NDA & NA (II) 2025 Exam Result', description: 'Results for the National Defence Academy exam held in early September are expected to be announced.' }, { date: '2025-10-15', title: 'National Scholarship Portal (NSP) Registration Opens', description: 'Registrations begin for various central government scholarships for post-matric students.' }, { date: '2025-11-05', title: 'JEE Main 2026 (Session 1) Registration Starts', description: 'The application window opens for the first session of the Joint Entrance Examination for engineering.' }, { date: '2025-12-15', title: 'CLAT 2026 Exam Date', description: 'The Common Law Admission Test for admission to National Law Universities is scheduled.' }, { date: '2025-12-31', title: 'NSP Scholarship Application Deadline', description: 'Last day to submit applications on the National Scholarship Portal for most schemes.' }, { date: '2026-01-24', title: 'JEE Main 2026 (Session 1) Exam Window', description: 'The first session of the JEE Main exam is scheduled between January 24th and February 1st.' }, { date: '2026-02-15', title: 'CBSE/State Board (Class 12th) Exams Begin', description: 'Board examinations for Class 12th are scheduled to start across the country.' }, { date: '2026-02-27', title: 'CUET-UG 2026 Application Window Opens', description: 'Registration for the Common University Entrance Test for undergraduate programs begins.' }, { date: '2026-03-01', title: 'JEE Main 2026 (Session 2) Registration Starts', description: 'The application window opens for the second session of the JEE Main exam.' }, { date: '2026-03-05', title: 'NEET-UG 2026 Registration Starts', description: 'The application process for the National Eligibility cum Entrance Test for medical courses begins.' }, { date: '2026-04-06', title: 'JEE Main 2026 (Session 2) Exam Window', description: 'The second session of the JEE Main exam is scheduled from April 6th to April 15th.' }, { date: '2026-05-05', title: 'NEET-UG 2026 Exam Date', description: 'The national entrance test for admission to MBBS, BDS, and other medical courses will be held.' }, { date: '2026-05-15', title: 'CUET-UG 2026 Exam Window', description: 'The Common University Entrance Test (CUET) exams are scheduled between May 15th and May 31st.' }, { date: '2026-06-10', title: 'JEE Advanced 2026 Exam Date', description: 'The entrance exam for admission to the Indian Institutes of Technology (IITs) will be conducted.' }, { date: '2026-06-20', title: 'NEET-UG 2026 Result Declaration', description: 'Results for the medical entrance examination are expected to be announced.' }, { date: '2026-07-01', title: 'JOSAA/Medical Counselling Begins', description: 'Joint Seat Allocation Authority (JoSAA) and medical counselling processes for admissions usually begin.' }];
    const resourcesData = {
        scholarships: {
            title: 'Scholarship Portals',
            icon: 'graduation-cap',
            color: 'blue',
            items: [
                { name: 'National Scholarship Portal (NSP)', desc: 'A one-stop solution for various scholarships by the Government of India.', link: 'https://scholarships.gov.in/' },
                { name: 'PMSSS for J&K Students', desc: 'Prime Minister\'s Special Scholarship Scheme for students from J&K and Ladakh.', link: 'https://www.aicte-jk-scholarship-gov.in/' },
                { name: 'J&K Social Welfare Department Scholarships', desc: 'Various state-level scholarships for different categories.', link: 'https://jkdswdj.jk.gov.in/' }
            ]
        },
        ebooks: {
            title: 'Free E-Books & Study Materials',
            icon: 'book-open-check',
            color: 'green',
            items: [
                { name: 'NCERT Textbooks', desc: 'Download official NCERT textbooks for all subjects from Class I to XII.', link: 'https://ncert.nic.in/textbook.php' },
                { name: 'N-LIST (INFLIBNET)', desc: 'Access to e-resources including e-books and e-journals for college students.', link: 'https://nlist.inflibnet.ac.in/' },
                { name: 'Swayam', desc: 'Free online courses with study materials from top Indian universities.', link: 'https://swayam.gov.in/' }
            ]
        },
        boards: {
            title: 'Official Education Boards',
            icon: 'building-2',
            color: 'purple',
            items: [
                { name: 'J&K Board of School Education (JKBOSE)', desc: 'Official website for notifications, results, and curriculum.', link: 'https://www.jkbose.nic.in/' },
                { name: 'Central Board of Secondary Education (CBSE)', desc: 'Official website for CBSE-affiliated schools.', link: 'https://www.cbse.gov.in/' },
                { name: 'National Testing Agency (NTA)', desc: 'Conducts major entrance exams like JEE, NEET, CUET.', link: 'https://www.nta.ac.in/' }
            ]
        }
    };

    // --- CORE APPLICATION LOGIC ---
    const views = document.querySelectorAll('.view');
    const navLinks = document.querySelectorAll('.nav-link');
    function showView(viewId) { views.forEach(view => view.classList.remove('active')); const activeView = document.getElementById(viewId); activeView.classList.add('active'); if (viewId === 'career-paths') { initCareerPaths(); } if (viewId === 'dashboard') { animateDashboardCards(); } window.scrollTo(0, 0); document.getElementById('mobile-menu').classList.add('hidden'); }
    navLinks.forEach(link => { link.addEventListener('click', (e) => { e.preventDefault(); const viewId = link.getAttribute('data-view'); showView(viewId); }); });
    document.getElementById('mobile-menu-button').addEventListener('click', () => { document.getElementById('mobile-menu').classList.toggle('hidden'); });
    let currentQuestionIndex = 0, scores = { science: 0, arts: 0, commerce: 0 };
    const quizContainer = document.getElementById('quiz-container'), quizResultContainer = document.getElementById('quiz-result');
    function startQuiz() { currentQuestionIndex = 0; scores = { science: 0, arts: 0, commerce: 0 }; quizContainer.classList.remove('hidden'); quizResultContainer.classList.add('hidden'); renderQuestion(); }
    function renderQuestion() { if (currentQuestionIndex >= quizQuestions.length) { showResult(); return; } const question = quizQuestions[currentQuestionIndex]; quizContainer.innerHTML = `<div class="quiz-question-container"><div class="text-sm text-gray-500 mb-2">Question ${currentQuestionIndex + 1} of ${quizQuestions.length}</div><h3 class="text-2xl font-semibold mb-6">${question.question}</h3><div class="space-y-4">${question.options.map((opt) => `<button class="quiz-option w-full text-left p-4 bg-gray-100 rounded-lg hover:bg-gray-200" data-stream="${opt.stream}">${opt.text}</button>`).join('')}</div></div>`; document.querySelectorAll('.quiz-option').forEach(button => button.addEventListener('click', handleAnswer)); }
    function handleAnswer(e) { scores[e.target.dataset.stream]++; currentQuestionIndex++; renderQuestion(); }
    function showResult() {
        const maxScore = Math.max(...Object.values(scores));
        const recommendedStream = Object.keys(scores).find(key => scores[key] === maxScore) || 'science';
        const keyMap = { science: 'engineeringCse', arts: 'law', commerce: 'managementHotel' };
        const recommendedKey = keyMap[recommendedStream];
        const recommendationData = careerDataAfter12th[recommendedKey];
        quizContainer.classList.add('hidden');
        quizResultContainer.classList.remove('hidden');
        const recommendationEl = document.getElementById('recommendation');
        recommendationEl.textContent = recommendationData.title;
        recommendationEl.className = `text-3xl font-bold text-${recommendationData.color}-600 my-4 p-4 bg-${recommendationData.color}-50 rounded-lg`;
        document.getElementById('explore-recommendation-btn').onclick = () => { showView('career-paths'); renderPaths('after12th'); };
    }
    function initCareerPaths() { const choiceContainer = document.getElementById('career-choice-container'), contentContainer = document.getElementById('career-path-content'); contentContainer.innerHTML = ''; choiceContainer.innerHTML = `<h3 class="text-2xl font-semibold mb-6">First, tell us your current stage:</h3><div class="flex flex-wrap justify-center gap-4"><button id="btn-after-10" class="custom-button">Completed 10th</button><button id="btn-after-12" class="custom-button bg-green-600 hover:bg-green-700">Completed 12th</button></div>`; document.getElementById('btn-after-10').addEventListener('click', () => renderPaths('after10th')); document.getElementById('btn-after-12').addEventListener('click', () => renderPaths('after12th')); }

    function renderPaths(level) {
        const choiceContainer = document.getElementById('career-choice-container');
        const contentContainer = document.getElementById('career-path-content');
        const data = (level === 'after10th') ? careerDataAfter10th : careerDataAfter12th;
        const title = (level === 'after10th') ? 'Career Options After 10th' : 'Career Paths After 12th';

        choiceContainer.innerHTML = `<div class="flex justify-between items-center mb-6"><h3 class="text-3xl font-bold">${title}</h3><button id="btn-back-to-choice" class="px-4 py-2 bg-gray-200 text-gray-700 font-semibold rounded-lg hover:bg-gray-300 transition-colors flex items-center gap-2"><i data-lucide="arrow-left" class="w-4 h-4"></i> Back</button></div>`;
        contentContainer.innerHTML = '';

        Object.keys(data).forEach((key, index) => {
            const item = data[key];
            const card = document.createElement('div');
            card.className = `bg-white p-6 rounded-lg shadow-md border-t-4 border-${item.color}-500 flex flex-col animated-card`;
            card.style.animationDelay = `${index * 100}ms`;

            let contentHTML = `
                <div class="flex items-center space-x-3 mb-4">
                    <i data-lucide="${item.icon}" class="text-${item.color}-600"></i>
                    <h3 class="text-2xl font-bold text-gray-800">${item.title}</h3>
                </div>
                <p class="text-gray-600 mb-4 flex-grow">${item.description}</p>
                <div class="space-y-4 text-sm">`;

            if (level === 'after10th') {
                contentHTML += `<div><h4 class="font-semibold text-gray-700 mb-2">Key Info:</h4><ul class="list-disc list-inside text-gray-600 space-y-1">${item.options.map(o => `<li>${o}</li>`).join('')}</ul></div>`;
            } else {
                if (item.eligibility) contentHTML += `<div><h4 class="font-semibold text-gray-700">Eligibility:</h4><p class="text-gray-600">${item.eligibility}</p></div>`;
                if (item.entranceExams?.length) contentHTML += `<div><h4 class="font-semibold text-gray-700">Top Entrance Exams:</h4><p class="text-gray-600">${item.entranceExams.join(', ')}</p></div>`;
                if (item.topCareers?.length) contentHTML += `<div><h4 class="font-semibold text-gray-700">Top Career Paths:</h4><ul class="list-disc list-inside text-gray-600">${item.topCareers.map(c => `<li>${c}</li>`).join('')}</ul></div>`;
                if (item.avgSalary) contentHTML += `<div><h4 class="font-semibold text-gray-700">Average Salary:</h4><p class="text-gray-600">${item.avgSalary}</p></div>`;
                if (item.topColleges?.length) contentHTML += `<div><h4 class="font-semibold text-gray-700">Top Colleges (Maharashtra Focus):</h4><ul class="list-disc list-inside text-gray-600">${item.topColleges.map(c => `<li>${c}</li>`).join('')}</ul></div>`;
                if (item.higherEducation?.length) contentHTML += `<div><h4 class="font-semibold text-gray-700">Higher Education:</h4><p class="text-gray-600">${item.higherEducation.join(', ')}</p></div>`;
            }

            contentHTML += `</div>`;
            card.innerHTML = contentHTML;
            contentContainer.appendChild(card);
        });

        document.getElementById('btn-back-to-choice').addEventListener('click', initCareerPaths);
        lucide.createIcons();
    }

    function renderColleges(filter = '') {
        const collegeList = document.getElementById('college-list');
        collegeList.innerHTML = '';
        const filteredColleges = collegeData.filter(c => c.name.toLowerCase().includes(filter.toLowerCase()) || c.city.toLowerCase().includes(filter.toLowerCase()));
        if (filteredColleges.length === 0) { collegeList.innerHTML = `<div class="text-center text-gray-500 p-8 bg-white rounded-lg shadow-md">No colleges found. Try a different search term.</div>`; return; }

        filteredColleges.forEach((college, index) => {
            const collegeCard = document.createElement('div');
            collegeCard.className = 'bg-white p-6 rounded-lg shadow-md animated-card';
            collegeCard.style.animationDelay = `${index * 100}ms`;
            collegeCard.innerHTML = `<h3 class="text-xl font-semibold text-blue-700">${college.name}</h3><p class="text-gray-500 mb-3">${college.city}</p><div class="mb-3"><h4 class="font-medium text-gray-700">Courses Offered:</h4><p class="text-gray-600">${college.courses.join(', ')}</p></div><div><h4 class="font-medium text-gray-700">Facilities:</h4><div class="flex flex-wrap gap-2 mt-1">${college.facilities.map(f => `<span class="bg-gray-200 text-gray-700 text-xs font-semibold px-2.5 py-0.5 rounded-full">${f}</span>`).join('')}</div></div>`;
            collegeList.appendChild(collegeCard);
        });
    }

    function initTimeline() {
        const container = document.getElementById('timeline-list');
        container.innerHTML = `<div class="relative border-l-2 border-blue-200 ml-4"></div>`;
        const timelineContainer = container.querySelector('div');
        timelineData.sort((a, b) => new Date(a.date) - new Date(b.date)).forEach(item => {
            const itemEl = document.createElement('div');
            itemEl.className = 'mb-8 ml-8';
            const formattedDate = new Date(item.date).toLocaleDateString('en-US', { year: 'numeric', month: 'long', day: 'numeric' });
            itemEl.innerHTML = `<span class="absolute flex items-center justify-center w-8 h-8 bg-blue-100 rounded-full -left-4 ring-8 ring-white"><i data-lucide="calendar-check" class="text-blue-600 w-5 h-5"></i></span><h3 class="flex items-center mb-1 text-lg font-semibold text-gray-900">${item.title}</h3><time class="block mb-2 text-sm font-normal leading-none text-gray-500">${formattedDate}</time><p class="text-base font-normal text-gray-600">${item.description}</p>`;
            timelineContainer.appendChild(itemEl);
        });
        lucide.createIcons();
    }

    function renderResources() {
        const container = document.getElementById('resources-content');
        container.innerHTML = '';
        Object.keys(resourcesData).forEach((key, index) => {
            const category = resourcesData[key];
            const categoryCard = document.createElement('div');
            categoryCard.className = `bg-white p-6 rounded-lg shadow-md border-l-4 border-${category.color}-500 animated-card`;
            categoryCard.style.animationDelay = `${index * 100}ms`;
            let itemsHTML = category.items.map(item => `<a href="${item.link}" target="_blank" rel="noopener noreferrer" class="block p-3 hover:bg-gray-100 rounded-md"><p class="font-semibold text-gray-800">${item.name}</p><p class="text-sm text-gray-600">${item.desc}</p></a>`).join('');
            categoryCard.innerHTML = `<div class="flex items-center space-x-3 mb-4"><i data-lucide="${category.icon}" class="text-${category.color}-600"></i><h3 class="text-2xl font-bold text-gray-800">${category.title}</h3></div><div class="space-y-2">${itemsHTML}</div>`;
            container.appendChild(categoryCard);
        });
        lucide.createIcons();
    }

    function animateDashboardCards() {
        const cards = document.querySelectorAll('#dashboard-cards > a');
        cards.forEach((card, index) => {
            card.classList.add('animated-card');
            card.style.animationDelay = `${index * 100}ms`;
        });
    }

    // --- INITIALIZATION ---
    function initApp() {
        document.querySelectorAll('.nav-link[data-view="aptitude-test"]').forEach(link => link.addEventListener('click', startQuiz));
        const collegeSearch = document.getElementById('college-search');
        collegeSearch.addEventListener('input', (e) => renderColleges(e.target.value));

        renderColleges();
        initTimeline();
        renderResources();
        animateDashboardCards();
        lucide.createIcons();





























































































































































# career-guida/* === Google Fonts Import === */
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

/* === CSS Variables (Theme) === */
:root {
    --primary-color: #4285F4; /* Google Blue */
    --primary-dark: #3367D6;
    --accent-color: #34A853; /* Google Green */
    --text-primary: #202124;
    --text-secondary: #5f6368;
    --bg-color: #f8f9fa;
    --surface-color: #ffffff;
    --border-color: #e0e0e0;
    --shadow-1: 0 1px 3px rgba(0,0,0,0.1), 0 1px 2px rgba(0,0,0,0.06);
    --shadow-2: 0 4px 6px rgba(0,0,0,0.1), 0 1px 3px rgba(0,0,0,0.08);
    --shadow-hover: 0 10px 15px rgba(0,0,0,0.1), 0 4px 6px rgba(0,0,0,0.05);
    --border-radius: 12px;
    --transition-speed: 0.3s;
}

/* === Base & Typography === */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Roboto', sans-serif;
    background-color: var(--bg-color);
    color: var(--text-primary);
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

h1, h2, h3, h4 {
    font-weight: 700;
    line-height: 1.2;
}

a {
    color: var(--primary-color);
    text-decoration: none;
    transition: color var(--transition-speed) ease;
}

a:hover {
    color: var(--primary-dark);
}

/* === Main Layout & Header === */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
}

header {
    background-color: rgba(255, 255, 255, 0.85);
    backdrop-filter: blur(10px);
    border-bottom: 1px solid var(--border-color);
}

.nav-link {
    position: relative;
    padding: 8px 0;
    font-weight: 500;
    transition: color var(--transition-speed) ease;
}

.nav-link::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 2px;
    background-color: var(--primary-color);
    transform: scaleX(0);
    transform-origin: bottom right;
    transition: transform var(--transition-speed) ease-out;
}

.nav-link:hover::after {
    transform: scaleX(1);
    transform-origin: bottom left;
}

/* === Views & Animations === */
.view {
    display: none;
}

.view.active {
    display: block;
    animation: fadeIn 0.6s ease-in-out;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
}

/* Staggered card animation */
.animated-card {
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 0.5s ease-out forwards;
}

@keyframes fadeInUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Slide-in animation for quiz */
@keyframes slide-in {
    0% { transform: translateX(100%); opacity: 0; }
    100% { transform: translateX(0); opacity: 1; }
}

.quiz-question-container {
    animation: slide-in 0.5s ease-in-out;
}

/* === Cards & Buttons === */
.card {
    background-color: var(--surface-color);
    border-radius: var(--border-radius);
    box-shadow: var(--shadow-1);
    transition: transform var(--transition-speed) ease, box-shadow var(--transition-speed) ease;
    border: 1px solid var(--border-color);
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-hover);
}

.custom-button {
    display: inline-block;
    padding: 12px 24px;
    font-weight: 700;
    border-radius: 8px;
    border: none;
    background-color: var(--primary-color);
    color: white;
    cursor: pointer;
    transition: background-color var(--transition-speed) ease, transform var(--transition-speed) ease;
    box-shadow: var(--shadow-1);
}

.custom-button:hover {
    background-color: var(--primary-dark);
    transform: translateY(-2px);
    box-shadow: var(--shadow-2);
}

/* === Specific View Styles === */

/* Dashboard */
#dashboard .nav-link {
    display: block;
    padding: 1.5rem;
    background-color: var(--surface-color);
    border-radius: var(--border-radius);
    box-shadow: var(--shadow-1);
    border: 1px solid var(--border-color);
}
#dashboard .nav-link::after { display: none; } /* Disable underline for dashboard cards */

/* Quiz */
#quiz-container {
    border: 1px solid var(--border-color);
}

.quiz-option {
    border: 2px solid var(--border-color) !important;
    transition: all var(--transition-speed) ease !important;
}

.quiz-option:hover {
    background-color: #e8f0fe !important; /* Light Google Blue */
    border-color: var(--primary-color) !important;
    transform: scale(1.02);
}

/* Career Paths */
#career-path-content .bg-white {
    transition: transform var(--transition-speed) ease, box-shadow var(--transition-speed) ease;
}
#career-path-content .bg-white:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-hover);
}

/* Timeline */
#timeline-list .relative {
    border-left-color: var(--primary-color);
}
#timeline-list span {
    background-color: #e8f0fe !important;
    /* ring-color is not a valid CSS property, so it's removed */
}

/* About Section on Dashboard */
.about-section {
    background: linear-gradient(135deg, #e8f0fe 0%, #f8f9fa 100%);
    border: 1px solid var(--border-color);
}nce1



