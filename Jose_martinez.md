
 var calcularIMC = function(peso, estatura){
 	return peso / (estatura * estatura);
 }

 var interpretarIMC = function(peso, estatura){
 	var imc = calcularIMC(peso, estatura);
 	if (imc > 24){
 		return "sobrepeso";
 	} else if (imc > 19) {
 		return "ok";
 	} else {
 		return "bajo peso";
 	}
 }

 var resultado = interpretarIMC(95);  <<-- 1. La primera 'i' va en minuscula. 2.  Aca falta colocarle un argumento.
 console.log(resultado);




 _------------------------------------------------------------------------------------------------------------------------------------
 
 Ejercicio de desarrolllo:
 
 Ejercicio 1: $("input[name='firstname']").val("Jose Martinez");
 Ejercicio 2 :$("[name='fav_day']").val("Monday");
 EJercicio 3: $("[name='first_name_label']").text("Jose Martinez");
 Ejercicio 4: var resul$("form:last").attr("name", "job_info");
 Ejercicio 8: t = $("[name='fav_day']").text();
 Ejercicio 5: $("input[value='female']").attr("checked",true);
 Ejercicio 6: $("form:first").attr("name", "personal_info");
 Ejercicio 7: $("form:last").attr("name", "job_info");

 Ejercicio 8: 
 $("form:eq(0)").before('<h1>Entrevista Personal</h1>');
 $("form:eq(1)").before('<h1>Entrevista Laboral</h1>');

 Ejercicio 9: $("input[name='lastname']").after("<h1>Gender</h1>");
 Ejercicio 10: $("input[name='lastname']").after("<br><p style='margin:0'>Correo:</p><input  type='email' name='email'>");
 Ejercicio 11 : $("form").attr("class","form");



 
 
 
 