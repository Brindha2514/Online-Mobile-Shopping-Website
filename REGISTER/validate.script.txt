<script>

        function validation(){
            var name=document.forms.register.name.value;
            var Fname=document.forms.register.Fname.value;
            var Mname=document.forms.register.Mname.value;
            var dob=document.forms.register.dob.value;
            var email=document.forms.register.email.value;
            var mobile=document.forms.register.mobile.value;
            var state=document.forms.register.state.value;
            var city=document.forms.register.city.value;
            if (name == "") {
                  alert("Please enter your name.");
                  name.select();
                  return false;
        }
        if (Fname == "") {
                  alert("Please enter your FatherName.");
                  Fname.select();
                  return false;
        }
        if (Mname == "") {
                  alert("Please enter your MotherName.");
                  Mname.select();
                  return false;
        }
        if (dob == "") {
                  alert("Please enter your DOB.");
                  dob.select();
                  return false;
        }
        if (email == "") {
                  alert("Please enter your EmailId.");
                  email.select();
                  return false;
        }
        if (mobile == "" ) {
                  alert("Please enter your MobileNo.");
                  mobile.select();
                  return false;
        }
        if (state == "") {
                  alert("Please enter your state.");
                  state.select();
                  return false;
        }
        
        if (city == "") {
                  alert("Please enter your City.");
                  city.select();
                  return false;
        }
        else{
            alert("Registered successfully!!");
        }
      } 
</script>

    