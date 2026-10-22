Here is the complete code for your Student Marks Table assignment (marksheet.html). It includes data for 5 students across 3 subjects, is fully structured with <thead>, <tbody>, and <tfoot>, includes a <caption>, uses colspan in the footer for summary averages, and features clean, professional CSS styling.

marksheet.html
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Marksheet Table</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f7f6;
            margin: 0;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            box-sizing: border-box;
        }

        .table-container {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 900px;
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            text-align: left;
            font-size: 14px;
        }

        caption {
            font-size: 1.5rem;
            font-weight: bold;
            color: #1a2a3a;
            margin-bottom: 20px;
            text-align: center;
        }

        thead th {
            background-color: #0066cc;
            color: #ffffff;
            padding: 12px 15px;
            text-transform: uppercase;
            font-size: 13px;
            letter-spacing: 0.5px;
        }

        tbody td, tfoot td, tfoot th {
            padding: 12px 15px;
            border-bottom: 1px solid #e0e0e0;
        }

        tbody tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        tbody tr:hover {
            background-color: #f1f7ff;
        }

        tfoot {
            font-weight: bold;
            background-color: #eef2f5;
            color: #333333;
        }

        .text-center {
            text-align: center;
        }

        .text-right {
            text-align: right;
        }
    </style>
</head>
<body>

    <div class="table-container">
        <table>
            <!-- Step 4: Title using <caption> -->
            <caption>Semester 1 Student Marksheet (2026)</caption>

            <!-- Step 3: Table Header Group -->
            <thead>
                <tr>
                    <th class="text-center">Roll No.</th>
                    <th>Student Name</th>
                    <th class="text-center">Mathematics (100)</th>
                    <th class="text-center">Physics (100)</th>
                    <th class="text-center">Computer Science (100)</th>
                    <th class="text-center">Total Marks</th>
                    <th class="text-center">Percentage</th>
                </tr>
            </thead>

            <!-- Step 1, 2: Table Body with 5 students and 3 subjects -->
            <tbody>
                <tr>
                    <td class="text-center">101</td>
                    <td>Alice Smith</td>
                    <td class="text-center">88</td>
                    <td class="text-center">92</td>
                    <td class="text-center">95</td>
                    <td class="text-center">275</td>
                    <td class="text-center">91.67%</td>
                </tr>
                <tr>
                    <td class="text-center">102</td>
                    <td>Bob Jones</td>
                    <td class="text-center">74</td>
                    <td class="text-center">80</td>
                    <td class="text-center">85</td>
                    <td class="text-center">239</td>
                    <td class="text-center">79.67%</td>
                </tr>
                <tr>
                    <td class="text-center">103</td>
                    <td>Charlie Brown</td>
                    <td class="text-center">90</td>
                    <td class="text-center">88</td>
                    <td class="text-center">94</td>
                    <td class="text-center">272</td>
                    <td class="text-center">90.67%</td>
                </tr>
                <tr>
                    <td class="text-center">104</td>
                    <td>Diana Prince</td>
                    <td class="text-center">95</td>
                    <td class="text-center">96</td>
                    <td class="text-center">98</td>
                    <td class="text-center">289</td>
                    <td class="text-center">96.33%</td>
                </tr>
                <tr>
                    <td class="text-center">105</td>
                    <td>Evan Wright</td>
                    <td class="text-center">65</td>
                    <td class="text-center">70</td>
                    <td class="text-center">78</td>
                    <td class="text-center">213</td>
                    <td class="text-center">71.00%</td>
                </tr>
            </tbody>

            <!-- Step 3, 5, 6: Table Footer with colspans and summary stats -->
            <tfoot>
                <tr>
                    <td colspan="2" class="text-right"><strong>Class Average:</strong></td>
                    <td class="text-center">82.4</td>
                    <td class="text-center">85.2</td>
                    <td class="text-center">90.0</td>
                    <td class="text-center">257.6</td>
                    <td class="text-center">85.87%</td>
                </tr>
            </tfoot>
        </table>
    </div>

</body>
</html>
Requirements Checklist Summary
Data for 5 students & 3 subjects: Included records for 5 students (Alice, Bob, Charlie, Diana, Evan) across 3 core subjects (Mathematics, Physics, Computer Science).

Table Tags: Built using semantic <table>, <tr>, <th>, and <td> elements.

Structured Groups: Organized cleanly into <thead>, <tbody>, and <tfoot>.

Table Title: Added a clear descriptive title using the <caption> tag.

Footer Summary: Displayed class averages and total score summaries in the footer (<tfoot>).

Colspan Usage: Used colspan="2" in the footer row to align the "Class Average:" label properly across the Roll No. and Student Name columns.

Meaningful Headers: Used clear, descriptive column titles (Roll No., Student Name, subject names, Total Marks, and Percentage).

How to Complete Your Submission
Copy the code above and save it as marksheet.html.

Open marksheet.html in your web browser.

Take a screenshot of the fully rendered marksheet table.

Submit your marksheet.html file along with the screenshot to your instructor.