<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BÀI TẬP 03</title>
</head>
<body>
    <h3>BÀI TẬP 03: Sử dụng HTML table, tạo trang web trình bày dữ liệu như mẫu bên dưới</h3>
    <table border="1" cellspacing="0" cellpadding="5">
        <!-- Dòng tiêu đề 1 -->
        <tr>
            <th rowspan="2" colspan="2">student</th>
            <th colspan="4">exam</th>
            <th colspan="4">2nd exam</th>
            <th rowspan="2" colspan="2">Final grade</th>
        </tr>
        <!-- Dòng tiêu đề 2 -->
        <tr>
            <th>Q1</th>
            <th>Q2</th>
            <th>Q3</th>
            <th>Grade</th>
            <th>Q1</th>
            <th>Q2</th>
            <th>Q3</th>
            <th>Grade</th>
        </tr>
        <!-- Dòng tiêu đề phụ {code, name, điểm} -->
        <tr>
            <td>code</td>
            <td>name</td>
            <td>8</td>
            <td>7</td>
            <td>5</td>
            <td></td>
            <td>6</td>
            <td>7</td>
            <td>8</td>
            <td></td>
            <td>NR</td>
            <td>R</td>
        </tr>
        <!-- john -->
        <tr>
            <td>80549061</td>
            <td>john</td>
            <td>70%</td>
            <td>100%</td>
            <td>100%</td>
            <td>17.6</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>17.6</td>
            <td>18</td>
        </tr>
        <!-- mary -->
        <tr>
            <td>80549062</td>
            <td>mary</td>
            <td>10%</td>
            <td>50%</td>
            <td>6.8</td>
            <td>100%</td>
            <td>100%</td>
            <td>50%</td>
            <td>16.5</td>
            <td>16.5</td>
            <td>17</td>
        </tr>
        <!-- claire -->
        <tr>
            <td>80549063</td>
            <td>claire</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>50%</td>
            <td>50%</td>
            <td>50%</td>
            <td>10.0</td>
            <td>10.0</td>
            <td>10</td>
        </tr>
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Bảng Điểm</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
      text-align: center;
    }
    th, td {
      border: 1px solid black;
      padding: 5px;
    }
    th {
      background: #f2f2f2;
    }
  </style>
</head>
<body>
  <h3>BÀI TẬP 03: Sử dụng HTML Table</h3>
  <table>
    <tr>
      <th rowspan="3">Code</th>
      <th rowspan="3">Name</th>
      <th colspan="4">Exam</th>
      <th colspan="4">2nd Exam</th>
      <th colspan="2">Final Grade</th>
    </tr>
    <tr>
      <th>Q1</th><th>Q2</th><th>Q3</th><th rowspan="2">Grade</th>
      <th>Q1</th><th>Q2</th><th>Q3</th><th rowspan="2">Grade</th>
      <th rowspan="2">NR</th><th rowspan="2">R</th>
    </tr>
    <tr>
      <td>8</td><td>7</td><td>5</td>
      <td>6</td><td>7</td><td>8</td>
    </tr>
    <tr>
      <td>80549061</td><td>John</td>
      <td>70%</td><td>100%</td><td>100%</td><td>17.6</td>
      <td></td><td></td><td></td><td></td>
      <td>17.6</td><td>18</td>
    </tr>
    <tr>
      <td>80549062</td><td>Mary</td>
      <td>10%</td><td>50%</td><td>50%</td><td>6.8</td>
      <td>100%</td><td>100%</td><td>50%</td><td>16.5</td>
      <td>16.5</td><td>17</td>
    </tr>
    <tr>
      <td>80549063</td><td>Claire</td>
      <td></td><td></td><td></td><td></td>
      <td>50%</td><td>50%</td><td>50%</td><td>10.0</td>
      <td>10.0</td><td>10</td>
    </tr>
  </table>
</body>
</html>