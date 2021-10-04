# EMI-code
<!DOCTYPE html>
<html>
<head>
	<title>EMI</title>
</head>
<body>


<!-- Script Code -->
<script>
	let loan=parseInt(prompt("Loan Amount"));
	let tenture=parseInt(prompt("Loan Tenture"));
	let intrest=parseInt(prompt("Intrest Rate"));
	let i=intrest/12/100;
	intrest=intrest/12/100;
	let Emi=loan*intrest*(((1+intrest)^tenture)/((1+intrest)^tenture-1));
	document.write(`Loan EMI ${Emi}`);
	document.write(`Total Intrest Payable ${Emi*tenture-loan}`);
	document.write(`Total payment (principal + Interest) ${Emi*tenture+loan}`);
</script>
</body>
</html>
