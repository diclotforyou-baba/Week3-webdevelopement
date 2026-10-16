
/* Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Roboto:wght@400;500;700&display=swap');

/* 1. Color Palette and Global Styles */
:root {
    --primary: #2563eb;
    --primary-dark: #1d4ed8;
    --background: #f1f5f9;
    --surface: #ffffff;
    --text: #1e293b;
    --muted: #64748b;
    --border: #e2e8f0;
    --table-alt: #f8fafc;
    --success: #15803d;
}

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 24px;
    background-color: var(--background);
    color: var(--text);
    font-family: 'Roboto', sans-serif;
    font-size: 16px;
    line-height: 1.6;
}

/* 2. Page Heading Card */
h1 {
    font-family: 'Poppins', sans-serif;
    font-size: 2rem;
    font-weight: 700;
    color: var(--primary);
    background-color: var(--surface);
    padding: 24px;
    margin: 0 auto 24px;
    border: 1px solid var(--border);
    border-radius: 14px;
    box-shadow: 0 4px 12px rgba(15, 23, 42, 0.05);
    text-align: center;
}

/* Section Headings */
h2,
h3 {
    font-family: 'Poppins', sans-serif;
    color: var(--text);
    font-weight: 600;
    margin-top: 0;
    margin-bottom: 18px;
}

/* 3. Add Expense Form Card */
form,
#expense-form,
.expense-form {
    background-color: var(--surface);
    padding: 24px;
    margin: 0 auto 24px;
    border: 1px solid var(--border);
    border-radius: 14px;
    box-shadow: 0 4px 12px rgba(15, 23, 42, 0.05);
}

/* Form Labels */
label {
    display: block;
    margin-bottom: 6px;
    font-weight: 500;
    color: var(--text);
}

/* Form Inputs and Select */
input,
select,
textarea {
    width: 100%;
    padding: 12px 14px;
    margin-bottom: 16px;
    border: 1px solid #cbd5e1;
    border-radius: 8px;
    background-color: #ffffff;
    color: var(--text);
    font-family: 'Roboto', sans-serif;
    font-size: 1rem;
    transition: border-color 0.2s, box-shadow 0.2s;
}

input:focus,
select:focus,
textarea:focus {
    outline: none;
    border-color: var(--primary);
    box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.15);
}

/* 4. Buttons */
button {
    padding: 12px 20px;
    border: none;
    border-radius: 8px;
    background-color: var(--primary);
    color: #ffffff;
    font-family: 'Roboto', sans-serif;
    font-size: 1rem;
    font-weight: 500;
    cursor: pointer;
    transition: background-color 0.2s, transform 0.2s;
}

button:hover {
    background-color: var(--primary-dark);
}

button:active {
    transform: translateY(1px);
}

/* 5. Expense Table Card */
table {
    width: 100%;
    border-collapse: collapse;
    background-color: var(--surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    overflow: hidden;
    margin: 0 auto 24px;
}

/* Table Header */
thead,
th {
    background-color: var(--primary);
    color: #ffffff;
    font-family: 'Poppins', sans-serif;
    font-weight: 600;
    text-align: left;
}

th,
td {
    padding: 14px 16px;
    border-bottom: 1px solid var(--border);
}

/* Alternating Row Colors */
tbody tr:nth-child(even) {
    background-color: var(--table-alt);
}

tbody tr:nth-child(odd) {
    background-color: var(--surface);
}

/* Table Hover Effect */
tbody tr:hover {
    background-color: #eff6ff;
}

/* Remove the last row's bottom border */
tbody tr:last-child td {
    border-bottom: none;
}

/* 6. Links */
a {
    color: var(--primary);
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* 7. Responsive Design */
@media (max-width: 600px) {
    body {
        padding: 12px;
        font-size: 15px;
    }

    h1 {
        font-size: 1.5rem;
        padding: 18px;
    }

    form,
    #expense-form,
    .expense-form {
        padding: 16px;
    }

    th,
    td {
        padding: 10px 8px;
        font-size: 0.9rem;
    }

    button {
        width: 100%;
    }
}
