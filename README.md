# web-page
web page creating
<!DOCTYPE html>
<html lang="en">
<head>
<title>Sample page</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
.content {
  width: 700px;
  height: 300px;
  float: right;
  border: 1px solid #ccc;
  background-color: gray;
}
body {
    background-color: gray;
}

/* Style the tab */
.tab {
  overflow: hidden;
  float: left;
  border: 1px solid #ccc;
  background-color: gray;
}
/* Header/logo Title */
.header {
  padding: 30px;
  text-align: center;
  background: rgb(109, 91, 91);
  color: black;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  border: 1px solid black;
  outline: none;
  cursor: pointer;
  padding: 15px 85px;
  transition: 0.3s;
  font-size: 20px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: rgb(19, 161, 204);
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>
</head>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>
</style>

<div class="header">
  <h1><b>About</b></h1>
  <p>Loreum ipsum dolar......</p>

</div>


</head>
<body> 

 <div class="row">
        <div class="side">
          <img src="C:\Users\173230\Desktop\image1.jpg" width=300 height=300>


    <div class= "content">


    <div class="tab">
        <button class="tablinks" onclick="openCity(event, 'History')">History</button>
        <button class="tablinks" onclick="openCity(event, 'Vision')">Vision</button>
        <button class="tablinks" onclick="openCity(event, 'Goals')">Goals</button>
      </div>

      <div id="History" class="tabcontent">
        <h3>History</h3>
        <p>We see the action of the hand striking the head, and we could assume many different emotions, justifications, and reactions, but the modification of the action implies the emotionless nature of the action, and reveals much about the character of the father, that he treats his animals and children equally.</p>
      </div>

      <div id="Vision" class="tabcontent">
        <h3>Vision</h3>
        <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. Maecenas nec odio et ante tincidunt tempus. Donec vitae sapien ut libero venenatis faucibus. Nullam quis ante. Etiam sit amet orci eget eros faucibus tincidunt. Duis leo. Sed fringilla mauris sit amet nibh. Donec sodales sagittis magna. Sed consequat, leo eget bibendum sodales, augue velit cursus nunc,</p> 
      </div>

      <div id="Goals" class="tabcontent">
        <h3>Goals</h3>
        <p>magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur? At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere</p>
      </div>
</html>
