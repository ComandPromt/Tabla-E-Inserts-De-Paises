~~~sql

CREATE TABLE NOMBRE_IDIOMAS (
  ID INT AUTO_INCREMENT PRIMARY KEY,
  NOMBRE VARCHAR(50) NOT NULL UNIQUE,
  IMG VARCHAR(50) UNIQUE,
  WORDS VARCHAR(250)
);

INSERT INTO NOMBRE_IDIOMAS (NOMBRE,IMG) VALUES
('Andorra',"ad.png"),('Emiratos Árabes',"ae.png"),('Afganistan',"af.png"),('Antigua Y Barbuda',"ag.png")
,('Anguilla',"ai.png"),('Albania',"al.png"),('Armenia',"am.png"),('Angola',"ao.png"),('Antártida',"aq.png")
,('Argentina',"ar.png"),('American Samoa',"as.png"),('Austria',"at.png"),('Australia',"au.png"),('Aruba',"aw.png")
,('Åland Islands',"ax.png"),('Azerbaiyan',"az.png"),('Bosnia Y Herzegovina',"ba.png"),('Barbados',"bb.png"),('Bangladesh',"bd.png")
,('Bélgica',"be.png"),('Burkina Faso',"bf.png"),('Bulgaria',"bg.png"),('Baréin',"bh.png"),('Burundi',"bi.png"),('Benin',"bj.png")
,('San Bartolomé',"bl.png"),('Bermuda',"bm.png"),('Brunei',"bn.png"),('Bolivia',"bo.png"),('Caribe Neerlandés',"bq.png")
,('Brasil',"br.png"),('Bahamas',"bs.png"),('Buthan',"bt.png"),('Isla Bouvet',"bv.png"),('Botswana',"bw.png")
,('Bielorusia',"by.png"),('Belice',"bz.png"),('Canadá',"ca.png"),('Isla Cocos',"cc.png"),('Congo',"cd.png")
,('República Central Africano',"cf.png"),('República Del Congo',"cg.png"),('Suiza',"ch.png")
,('Costa De Marfil',"ci.png"),('Islas Cook',"ck.png"),('Chile',"cl.png"),('Camerún',"cm.png"),('China',"cn.png")
,('Colombia',"co.png"),('Costa Rica',"cr.png"),('Cuba',"cu.png"),('Cabo Verde',"cv.png"),('Curacao',"cw.png")
,('Isla Navidad',"cx.png"),('Chipre',"cy.png"),('República Checha',"cz.png"),('Alemania',"de.png"),('Djibouti',"dj.png")
,('Dinamarca',"dk.png"),('Dominica',"dm.png"),('República Dominicana',"do.png")
,('Argelia',"dz.png"),('Ecuador',"ec.png"),('Estonia',"ee.png"),('Egipto',"eg.png"),('República Árabe Saharaui',"eh.png")
,('Eritrea',"er.png"),('Español',"es.png"),('Ethiopia',"et.png"),('Finlandia',"fi.png"),('Fiji',"fj.png"),('Falkland Islands',"fk.png"),
('Estados Federados De Micronesia',"fm.png"),('Islas Faroe',"fo.png"),('Francés',"fr.png"),('Gabón',"ga.png"),
('Reino Unido',"gb.png"),('Inglaterra',"gb-eng.png"), ('Irlanda Del Norte',"gb-nir.png"),('Escocia',"gb-sct.png"), 
('Gales',"gb-wls.png"), ('Granada',"gd.png"),('Georgia',"ge.png"),('Guayana Francesa',"gf.png"),
('Guernsey',"gg.png"),('Ghana',"gh.png"),('Gibraltar',"gi.png"),('Groenlandia',"gl.png"),
('Ghambia',"gm.png"),('Guinea',"gn.png"),('Guadalupe',"gp.png"),('Guinea Ecuatorial',"gq.png"),
('Grecia',"gr.png"),('Georgia del Sur y las Islas Sandwich del Sur',"gs.png"),('Guatemala',"gt.png")
,('Guam',"gu.png"),('Flag of Guinea-Bissau',"gw.png"),('Guyana',"gy.png"),('Hong Kong',"hk.png")
,('Islas Heard y McDonald',"hm.png"),('Honduras',"hn.png"),('Croacia',"hr.png"),('Haití',"ht.png"),('Hungría',"hu.png"),('Indonesia',"id.png")
,('Irlanda',"ie.png"),('Israel',"il.png"),('Isla Man',"im.png"),('India',"in.png"),
('Territorio Británico del Océano Índico',"io.png"),('Iraq',"iq.png"),('Irán',"ir.png"),('Islandia',"is.png"),
('Italia',"it.png"),('Jersey',"je.png"),('Jamaica',"jm.png"),('Jordania',"jo.png"),('Japón',"jp.png"),
('Kenia',"ke.png"),('Kirguistán',"kg.png"),('Camboya',"kh.png"),('Kiribati',"ki.png"),
('Comoras',"km.png"),('San cristóbal Y Nieves',"kn.png"),('Corea Del Norte',"kp.png"),
('Corea Del Sur',"kr.png"),('Kuwait',"kw.png"),('Islas Caimán',"ky.png"),('Kazakhstan',"kz.png"),
('Laos',"la.png"),('Líbano',"lb.png"),('Santa Lucía',"lc.png"),
('Liechtenstein',"li.png"),('Sri Lanka',"lk.png"),('Liberia',"lr.png")
,('Lesoto',"ls.png"),('Lituania',"lt.png"),('Luxemburgo',"lu.png"),('Letonia',"lv.png")
,('Libia',"ly.png"),('Marruecos',"ma.png"),('Monaco',"mc.png")
,('Moldavia',"md.png"),('Montenegro',"me.png"),('San Martín (Francia)',"mf.png")
,('Madagascar',"mg.png"),('Islas Marshall',"mh.png"),('Macedonia',"mk.png")
,('Mali',"ml.png"),('Birmania',"mm.png"),('Mongolia',"mn.png"),('Macao',"mo.png")
,('Islas Marianas del Norte',"mp.png"),('Martinica',"mq.png"),('Mauritania',"mr.png"),
('Montserrat',"ms.png"),('Malta',"mt.png"),('Mauricio',"mu.png"),
('Maldivas',"mv.png"),('Malawi',"mw.png"),('Mexico',"mx.png"),
('Malasia',"my.png"),('Mozambique',"mz.png"),('Namibia',"na.png"),('Nueva Caledonia',"nc.png"),
('Niger',"ne.png"),('Isla Norfolk',"nf.png"),('Nigeria',"ng.png"),
('Nicaragua',"ni.png"),('Países Bajos',"nl.png"),('Noruega',"no.png"),
('Nepal',"np.png"),('Nauru',"nr.png"),('Niue',"nu.png"),('Nueva Zelanda',"nz.png"),
('Omán',"om.png"),('Panamá',"pa.png"),('Perú',"pe.png"),('Polinesia Francesa',"pf.png"),('Papua Nueva Guinea',"pg.png"),
('Filipinas',"ph.png"),('Pakistán',"pk.png"),('Polonia',"pl.png"),('San Pedro y Miquelón',"pm.png"),
('Islas Pitcairn',"pn.png"),('Puerto Rico',"pr.png")
,('Palestina',"ps.png"),('Portugal',"pt.png"),('Palaos',"pw.png"),('Paraguay',"py.png"),
('Qatar',"qa.png"),('Reunión',"re.png"),('Rumanía',"ro.png"),('Serbia',"rs.png"),
('Rusia',"ru.png"),('Ruanda',"rw.png"),('Arabia Saudita',"sa.png"),('Islas Solomon',"sb.png"),
('Seychelles',"sc.png"),('Sudán',"sd.png"),('Suecia',"se.png"),('Singapur',"sg.png"),
('Santa Elena, Ascensión y Tristán de Acuña',"sh.png"),('Eslovenia',"si.png"),
('Svalbard and Jan Mayen',"sj.png"),('Eslovaquia',"sk.png"),('Sierra Leona',"sl.png"),
('San Marino',"sm.png"),('Senegal',"sn.png"),('Somalia',"so.png"),
('Surinam',"sr.png"),('Sudán Del Sur',"ss.png"),('Santo Tomé',"st.png"),('El Salvador',"sv.png"),
('San Martín',"sx.png"),('Siria',"sy.png"),('Eswatini',"sz.png"),
('Islas Turcas y Caicos',"tc.png"),('Chad',"td.png"),
('Bandera de las Tierras Australes y Antárticas Francesas',"tf.png"),('Togo',"tg.png"),
('Tailandia',"th.png"),('Tajikistán',"tj.png"),('Tokelau',"tk.png"),('Timor-Leste',"tl.png"),
('Turkmenistan',"tm.png"),('Tunisia',"tn.png"),('Tonga',"to.png"),('Turquía',"tr.png"),
('Trinidad Y Tobago',"tt.png"),('Tuvalu',"tv.png"),('Taiwán',"tw.png"),('Tanzania',"tz.png"),
('Ucrania',"ua.png"),('Uganda',"ug.png"),('Islas Ultramarinas Menores de Estados Unidos',"um.png"),('United States Of América',"us.png"),
('Uruguay',"uy.png"),('Uzbekistan',"uz.png"),('Vaticano',"va.png"),('San Vicente y las Granadinas',"vc.png"),
('Venezuela',"ve.png"),('Islas Vírgenes Británicas',"vg.png"),('United States Virgin Islands',"vi.png"),
('Vietnam',"vn.png"),('Vanuatu',"vu.png"),('Wallis y Futuna',"wf.png"),('Samoa',"ws.png"),('Kosovo',"xk.png"),
('Yemen',"ye.png"),('Mayotte',"yt.png"),('Sudáfrica',"za.png"),('Zambia',"zm.png"),('Zimbawe',"zw.png"),
('Cataluña',"catalan.png"),('Gallego',"galicia.png"),('Euskera',"euskera.png");
~~~
