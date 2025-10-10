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







<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Employee Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: #f9f9f9;
    }
    form {
      max-width: 800px;
      margin: auto;
      background: #fff;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    fieldset {
      margin-bottom: 20px;
      padding: 15px;
      border: 1px solid #aaa;
    }
    legend {
      font-weight: bold;
      padding: 0 10px;
    }
    .form-group {
      display: flex;
      margin-bottom: 10px;
    }
    .form-group label {
      width: 150px;
      font-weight: bold;
    }
    .form-group input,
    .form-group select,
    .form-group textarea {
      flex: 1;
      padding: 6px;
    }
    .radio-group,
    .checkbox-group {
      display: flex;
      align-items: center;
      gap: 10px;
    }
    textarea {
      height: 100px;
    }
    .actions {
      text-align: right;
    }
    .actions button {
      padding: 6px 12px;
      margin-left: 5px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .btn-submit {
      background: #007bff;
      color: #fff;
    }
    .btn-cancel {
      background: #aaa;
      color: #fff;
    }
  </style>
</head>
<body>

  <form>
    <!-- Basic Info -->
    <fieldset>
      <legend>Basic Info</legend>
      <div class="form-group">
        <label>Employee ID</label>
        <input type="text" value="9">
      </div>
      <div class="form-group">
        <label>Last Name</label>
        <input type="text" value="Dodsworth">
      </div>
      <div class="form-group">
        <label>First Name</label>
        <input type="text" value="Anne">
      </div>
      <div class="form-group">
        <label>Gender</label>
        <div class="radio-group">
          <label><input type="radio" name="gender"> Male</label>
          <label><input type="radio" name="gender" checked> Female</label>
          <label><input type="radio" name="gender"> XXX</label>
        </div>
      </div>
      <div class="form-group">
        <label>Title</label>
        <input type="text" value="Sales Representative">
      </div>
      <div class="form-group">
        <label>Suffix</label>
        <input type="text" value="Ms.">
      </div>
      <div class="form-group">
        <label>BirthDate</label>
        <input type="datetime-local" value="1969-07-02T00:00">
      </div>
      <div class="form-group">
        <label>HireDate</label>
        <input type="datetime-local" value="1994-11-15T00:00">
      </div>
      <div class="form-group">
        <label>SSN #</label>
        <input type="text">
      </div>
      <div class="form-group">
        <label>Reports To</label>
        <select>
          <option>Buchanan</option>
        </select>
      </div>
    </fieldset>

    <!-- Contact Info -->
    <fieldset>
      <legend>Contact Info</legend>
      <div class="form-group">
        <label>Email</label>
        <input type="email" placeholder="name@example.com">
      </div>
      <div class="form-group">
        <label>Address</label>
        <input type="text" value="7 Houndstooth Rd.">
      </div>
      <div class="form-group">
        <label>City</label>
        <input type="text" value="London">
      </div>
      <div class="form-group">
        <label>Region</label>
        <input type="text">
      </div>
      <div class="form-group">
        <label>Postal Code</label>
        <input type="text" value="WG2 7LT">
      </div>
      <div class="form-group">
        <label>Country</label>
        <select>
          <option>Russian Federation</option>
          <option>United Kingdom</option>
          <option>USA</option>
        </select>
      </div>
      <div class="form-group">
        <label>US Phone</label>
        <input type="tel" value="(234)234-2342">
      </div>
      <div class="form-group">
        <label>Photo</label>
        <input type="text" value="EmplD9.bmp">
      </div>
    </fieldset>

    <!-- Optional Info -->
    <fieldset>
      <legend>Optional Info</legend>
      <div class="form-group">
        <label>Notes</label>
        <textarea>Anne has a BA degree in English from St. Lawrence College.
She is fluent in French and German.</textarea>
      </div>
      <div class="form-group">
        <label>Preferred Shift</label>
        <div class="radio-group">
          <label><input type="radio" name="shift"> Regular</label>
          <label><input type="radio" name="shift" checked> Gravy Yard</label>
        </div>
      </div>
      <div class="form-group">
        <label>Active?</label>
        <div class="checkbox-group">
          <input type="checkbox" checked>
        </div>
      </div>
      <div class="form-group">
        <label>Are you human?</label>
        <input type="text" value="TIDAWO">
      </div>
    </fieldset>

    <!-- Buttons -->
    <div class="actions">
      <button type="submit" class="btn-submit">Submit</button>
      <button type="reset" class="btn-cancel">Cancel</button>
    </div>
  </form>

</body>
</html>














Bài tập 2: dàn trang 
<!DOCTYPE html>
<html lang="vi">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bố cục Flexbox</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #fff;
            font-family: sans-serif;
        }

        .row {
            display: flex;
            align-items: flex-end;
            gap: 12px;
        }

        .block {
            background: #666;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            font-weight: bold;
            border-radius: 4px;
        }


        .h-20 {
            height: 20vh;
            width: 20vh;
        }


        .h-30 {
            height: 30vh;
            width: 12vh;
        }


        .h-15 {
            height: 15vh;
            width: 17vh;
        }


        .h-35 {
            height: 35vh;
            width: 18vh;
        }


        .h-50 {
            height: 50vh;
            width: 20vh;
        }
    </style>
</head>

<body>
    <div class="row">
        <div class="block h-20">20vh</div>
        <div class="block h-30">30vh</div>
        <div class="block h-15">15vh</div>
        <div class="block h-35">35vh</div>
        <div class="block h-50">50vh</div>
        <div class="block h-20">20vh</div> <!-- khối 20 cuối cùng bằng khối 20 đầu -->
    </div>
</body>

</html>