# Web
Web de prueba
<! DOCTYPE html>
< html >
< cabeza >
	< título > Iniciar sesión </ título >
	< meta  charset = " utf-8 " >
	< link  rel = " stylesheet "  type = " text / css "  href = " ./css/materialize.min.css " >
	< link  rel = " stylesheet "  type = " text / css "  href = ./css/style.css >
	< link  rel = " stylesheet "  type = " text / css "  href = " ./css/sweetalert2.min.css " >
</ cabeza >
< body  class = " pink " >
		< div  class = " container "  hidden = " " >
			< form  action = " "  class = " center " >
				< h5 > Iniciar sesión </ h5 >
				< div  class = " input-field col s3 " >
					< label  for = " Usuario " > Usuario </ label >
					< input  id = " Usuario "  type = " text "  name = " Usuario "  class = " col s2 " >
				</ div >
				< div  class = " input-field col s3 " >
					< label  for = " Password " > Contraseña </ label >
					< input  id = " Contraseña "  type = " Password "  name = " Password " >
				</ div >
				< div  class = " card-actions " >
					< input  id = " entrar "  type = " button "  class = " btn blue "  value = " Entrar " >
				</ div >
			</ form >
		</ div >
		< script  src = " ./js/jquery.js " > </ script >
		< script  src = " ./js/materialize.min.js " > </ script >
		< script  src = " ./js/actions.js " > </ script >
		< script  src = " ./js/sweetalert2.min.js " > </ script >
</ cuerpo >
</ html >
