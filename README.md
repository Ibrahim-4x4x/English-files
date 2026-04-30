<T.Ibrahim>
<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unit 7 English Quiz</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f8fafc; }
        .card { background: white; border-radius: 12px; box-shadow: 0 2px 10px rgba(0,0,0,0.05); margin-bottom: 24px; padding: 24px; border: 1px solid #e2e8f0; }
        .hidden { display: none; }
        input[type="radio"] { cursor: pointer; }
        .section-title { color: #1e40af; border-left: 4px solid #1e40af; padding-left: 12px; margin-bottom: 20px; font-weight: bold; }
    </style>
</head>
<body class="p-4 md:p-10">

    <div id="main-container" class="max-w-4xl mx-auto">
        <!-- Header -->
        <header class="text-center mb-10">
            <h1 class="text-4xl font-extrabold text-blue-800">Unit 7: Communication & Life</h1>
            <p class="text-gray-500 mt-2 font-medium">Final Score: 10 Marks</p>
        </header>

        <!-- Student Login -->
        <div id="auth-section" class="card text-center">
            <h2 class="text-2xl font-semibold mb-6">Student Information</h2>
            <div class="max-w-md mx-auto space-y-4">
                <input type="text" id="student-name" class="w-full p-3 border-2 border-gray-200 rounded-lg focus:border-blue-500 outline-none transition" placeholder="Enter your full name...">
                <button onclick="startQuiz()" id="start-btn" class="w-full bg-blue-600 text-white py-3 rounded-lg font-bold hover:bg-blue-700 transition shadow-lg">Start Quiz</button>
            </div>
            <p class="text-red-500 text-sm mt-4">* You can only take this quiz once.</p>
        </div>

        <!-- Quiz Form -->
        <form id="quiz-form" class="hidden">
            
            <!-- Section 1: Vocabulary (4 Marks) -->
            <div class="card">
                <h3 class="section-title text-xl">Section 1: Vocabulary & Usage (4 Marks)</h3>
                
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="space-y-3">
                        <p class="font-medium">1. Lisa likes to _______ to friends online in the evening.</p>
                        <div class="space-y-1 ml-4 text-gray-700">
                            <label class="block"><input type="radio" name="q1" value="chat"> chat</label>
                            <label class="block"><input type="radio" name="q1" value="receive"> receive</label>
                            <label class="block"><input type="radio" name="q1" value="get"> get</label>
                        </div>
                    </div>

                    <div class="space-y-3">
                        <p class="font-medium">2. My dad doesn't like _______ social media.</p>
                        <div class="space-y-1 ml-4 text-gray-700">
                            <label class="block"><input type="radio" name="q2" value="writing"> writing</label>
                            <label class="block"><input type="radio" name="q2" value="using"> using</label>
                            <label class="block"><input type="radio" name="q2" value="seeing"> seeing</label>
                        </div>
                    </div>

                    <div class="space-y-3">
                        <p class="font-medium">3. We'd like to _______ a vlog about life in the UAE.</p>
                        <div class="space-y-1 ml-4 text-gray-700">
                            <label class="block"><input type="radio" name="q3" value="watch"> watch</label>
                            <label class="block"><input type="radio" name="q3" value="get"> get</label>
                            <label class="block"><input type="radio" name="q3" value="use"> use</label>
                        </div>
                    </div>

                    <div class="space-y-3">
                        <p class="font-medium">4. How often do you _______ an emoji in messages?</p>
                        <div class="space-y-1 ml-4 text-gray-700">
                            <label class="block"><input type="radio" name="q4" value="insert"> insert</label>
                            <label class="block"><input type="radio" name="q4" value="tell"> tell</label>
                            <label class="block"><input type="radio" name="q4" value="have"> have</label>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Section 2: Opposites (2 Marks) -->
            <div class="card">
                <h3 class="section-title text-xl">Section 2: Opposites (2 Marks)</h3>
                <div class="space-y-4">
                    <div class="flex items-center justify-between p-3 bg-slate-50 rounded-lg">
                        <span class="font-bold">I can't receive or _____ a message.</span>
                        <select name="opp1" class="border-2 p-2 rounded-md focus:border-blue-400">
                            <option value="">Select...</option>
                            <option value="send">send</option>
                            <option value="tell">tell</option>
                        </select>
                    </div>
                    <div class="flex items-center justify-between p-3 bg-slate-50 rounded-lg">
                        <span class="font-bold">I usually get on _____ with people.</span>
                        <select name="opp2" class="border-2 p-2 rounded-md focus:border-blue-400">
                            <option value="">Select...</option>
                            <option value="badly">badly</option>
                            <option value="well">well</option>
                        </select>
                    </div>
                </div>
            </div>

            <!-- Section 3: Reading - Sheku Kanneh-Mason (4 Marks) -->
            <div class="card">
                <h3 class="section-title text-xl">Section 3: Reading Comprehension (4 Marks)</h3>
                <div class="mb-4 p-4 bg-blue-50 rounded italic text-sm">
                    Sheku Kanneh-Mason was born in 1999. At 5, he played piano. At 6, he played cello. In 2016, he won a UK competition. In 2018, he played in London for millions.
                </div>
                
                <div class="space-y-4">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div class="p-2 border rounded">
                            <p class="text-sm font-semibold mb-2">How old was Sheku when he started playing the Cello?</p>
                            <input type="number" name="r1" class="w-full p-2 border rounded" placeholder="Enter age...">
                        </div>
                        <div class="p-2 border rounded">
                            <p class="text-sm font-semibold mb-2">In which year did millions watch him on TV?</p>
                            <input type="number" name="r2" class="w-full p-2 border rounded" placeholder="Enter year...">
                        </div>
                        <div class="p-2 border rounded">
                            <p class="text-sm font-semibold mb-2">Which instrument does Sheku play primarily?</p>
                            <select name="r3" class="w-full p-2 border rounded">
                                <option value="">Select...</option>
                                <option value="piano">Piano</option>
                                <option value="cello">Cello</option>
                                <option value="viola">Viola</option>
                            </select>
                        </div>
                        <div class="p-2 border rounded">
                            <p class="text-sm font-semibold mb-2">How many sisters does Sheku have?</p>
                            <input type="number" name="r4" class="w-full p-2 border rounded" placeholder="Number of sisters...">
                        </div>
                    </div>
                </div>
            </div>

            <button type="button" onclick="submitQuiz()" class="w-full bg-green-600 text-white py-4 rounded-xl font-bold text-2xl hover:bg-green-700 transition shadow-xl mb-10">Submit All Answers</button>
        </form>

        <!-- Final Result Screen -->
        <div id="result-message" class="hidden card text-center py-10">
            <div id="icon-box" class="mb-4 text-6xl text-green-500">✔</div>
            <h2 class="text-3xl font-bold text-gray-800 mb-2">Quiz Submitted!</h2>
            <p id="score-display" class="text-4xl font-extrabold text-blue-600 mb-6"></p>
            <p class="text-gray-500">Your results have been sent to your teacher.</p>
            <button onclick="location.reload()" class="mt-8 text-blue-600 underline">Refresh Page</button>
        </div>
    </div>

    <script>
        // --- EmailJS Configuration ---
        const SERVICE_ID = "service_wl6tuqv"; 
        const TEMPLATE_ID = "template_k48h71x";
        const PUBLIC_KEY = "1a5gXooNvC3I21xjV";

        emailjs.init(PUBLIC_KEY);

        const storageKey = "student_quiz_v2_done";

        window.onload = () => {
            if (localStorage.getItem(storageKey)) {
                showAlreadyDone();
            }
        };

        function startQuiz() {
            const name = document.getElementById('student-name').value;
            if (!name.trim()) {
                alert("Please enter your name!");
                return;
            }
            document.getElementById('auth-section').classList.add('hidden');
            document.getElementById('quiz-form').classList.remove('hidden');
            window.scrollTo(0, 0);
        }

        function showAlreadyDone() {
            document.getElementById('auth-section').classList.add('hidden');
            document.getElementById('quiz-form').classList.add('hidden');
            const res = document.getElementById('result-message');
            res.classList.remove('hidden');
            res.innerHTML = `
                <div class="text-red-500 text-6xl mb-4">⚠</div>
                <h2 class="text-2xl font-bold mb-2">Access Denied</h2>
                <p>You have already completed this test. Multiple attempts are not allowed.</p>
            `;
        }

        async function submitQuiz() {
            const form = document.getElementById('quiz-form');
            const formData = new FormData(form);
            const studentName = document.getElementById('student-name').value;

            // Scoring Logic (Total 10)
            let score = 0;
            // Section 1 (4 points)
            if (formData.get('q1') === 'chat') score++;
            if (formData.get('q2') === 'using') score++;
            if (formData.get('q3') === 'watch') score++;
            if (formData.get('q4') === 'insert') score++;
            // Section 2 (2 points)
            if (formData.get('opp1') === 'send') score++;
            if (formData.get('opp2') === 'well') score++;
            // Section 3 (4 points)
            if (formData.get('r1') === '6') score++;
            if (formData.get('r2') === '2018') score++;
            if (formData.get('r3') === 'cello') score++;
            if (formData.get('r4') === '5') score++;

            const finalScore = `${score} / 10`;

            const btn = document.querySelector('button[onclick="submitQuiz()"]');
            btn.disabled = true;
            btn.innerText = "Sending Results...";

            const templateParams = {
                to_name: "Teacher",
                from_name: studentName,
                score: finalScore,
                details: Array.from(formData.entries()).map(e => `${e[0]}: ${e[1]}`).join(" | ")
            };

            try {
                // In production, uncomment the line below:
                // await emailjs.send(SERVICE_ID, TEMPLATE_ID, templateParams);
                
                localStorage.setItem(storageKey, "true");
                form.classList.add('hidden');
                document.getElementById('result-message').classList.remove('hidden');
                document.getElementById('score-display').innerText = `Your Score: ${finalScore}`;
                window.scrollTo(0, 0);
            } catch (error) {
                alert("Error sending email. Please check your connection.");
                btn.disabled = false;
                btn.innerText = "Submit All Answers";
            }
        }
    </script>
</body>
</html>
