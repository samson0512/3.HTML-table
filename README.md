# 3.HTML-table
# program:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weekly Schedule</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Weekly Schedule</h1>
    <table>
        <thead>
            <tr>
                <th>Time Slot</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
                <th>Sunday</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Morning</td>
                <td>Exercise</td>
                <td>Team Meeting</td>
                <td>Project Work</td>
                <td>Exercise</td>
                <td>Client Call</td>
                <td>Hiking</td>
                <td>Relaxing</td>
            </tr>
            <tr>
                <td>Afternoon</td>
                <td>Work</td>
                <td>Work</td>
                <td>Work</td>
                <td>Work</td>
                <td>Work</td>
                <td>Shopping</td>
                <td>Family Time</td>
            </tr>
            <tr>
                <td>Evening</td>
                <td>Dinner with Friends</td>
                <td>Gym</td>
                <td>Reading</td>
                <td>Gym</td>
                <td>Movie Night</td>
                <td>Party</td>
                <td>Relaxing</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
# output:
![image](https://github.com/samson0512/3.HTML-table/assets/172907275/1fbc7910-3b6e-4b67-a092-3171507c0b5f)
