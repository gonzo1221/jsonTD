En este ejemplo Nico vas a ver un ejemplo con todos los elementos que se pueden enviar por JSON a Traindata.

Recordá:
1. <b>Tipo de coberturas:</b><br>
   key <b>"tipo_cobertura"</b> (string): "Plan 36", "Plan 39", "Plan Selecto" o "Plan Privilegio".

2. <b>Tipo de llantas (Rodaje/Auxilio):</b><br>
   key <b>"lla_rod_tipo"</b> o <b>"lla_aux_tipo"</b>: "chapa", "aleacion", "especial" o "ruedin". <i>En minúsculas y sin tildes</i>

3. <b>Comentarios desde la compañia o PAS:</b><br>
   key <b>"detalles_siniestro"</b> (string)

4. <b>Vistas fotográficas:</b><br>
   key <b>"vistas_fotograficas"</b> (string) tipo base64. Solo admite una foto por ahora, si necesitás más avisame.
