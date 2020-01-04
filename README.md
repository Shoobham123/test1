<!DOCTYPE Html>
<head>
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" type="text/css" href="C:\Users\Bhaskarwar\Downloads\css\bootstrap.min.css">
  <script src="C:\Users\Bhaskarwar\Downloads\js\jquery.min.js"></script>
  <script src="C:\Users\Bhaskarwar\Downloads\js\bootstrap.min.js"></script>
  <style>
      table{
          text-align:center;
          height:600px;
          
      }
      th{
          text-align:center;
          background-color:lightgreen;
      }
      td{
          background-color:lightskyblue;
          
          
      }
      #body{
        background-image: url(test.jpga);
        
      }
      
  </style>
</head>
<body>
<div class="container-fluid" style="border:1px solid black;">
<div class="row">
<div class="col-sm-4" style="border:1px solid black;">

    <table class="table">
        <thead>
            <tr>
                <th>User List</th>
            </tr>    
        </thead>
        <tbody>
            <tr>
                <td>Shubham Bhaskarwar</td>
            </tr>
            <tr>
                <td>Gaurav Sali</td>
            </tr>
            <tr>
                <td>Shreyas Chinchore</td>
            </tr>
            <tr>
                <td>Sanjay Kholgade</td>
            </tr>
            <tr>
                <td>Vaibhav Pawar</td>
            </tr>
        </tbody> 
    </table>       
    

</div>

<div class="col-sm-8" style="border:1px solid black;" id="body">
        
    <div class="form-group">
        <label>Name</label>
        <input type="text" class="form-control">
        <label>Email-Id</label>
        <input type="email" class="form-control">
        <label>Mobile Number</label>
        <input type="number" class="form-control">
        <label>Address</label>
        <input type="text" class="form-control">
    </div>    

</div>

</div>
</div>
</body>
</html>
