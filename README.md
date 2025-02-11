# DSCCTF

BY FOLLOWING CULES WE CAN TRY DIFFERENT VARIATION TO GET THE FINAL FLAG 

$ curl -s https://secretgroup.ctf.dscjssstuniv.in/
<p>Not an agent of the <b>dsc-4dm1n</b> secure browser!</p>

$ curl -H "Referer: https://secretgroup.ctf.dscjssstuniv.in/"      -H "User-*/*"pt: fl4g"      -H "Give-Flag: true"      https://secretgroup.ctf.dscjssstuniv.in/
<p>Does not Accept <b>fl4g</b></p>

$ curl -H "Referer: https://secretgroup.ctf.dscjssstuniv.in/"      -H "User-Agent:true-4dm1n"      -H "Accept: fl4g"      -H "Give-Flag: 7ru3"      https://secretgroup.ctf.dscjssstuniv.in/
<b>Give-Flag</b> is not <b>7ru3</b>

$ curl -H "Referer: https://secretgroup.ctf.dscjssstuniv.in/"      -H "User-Agent: dsc-4dm1n"      -H "Accept: fl4g"      -H "Give-Flag: 7ru3"      https://secretgroup.ctf.dscjssstuniv.in/
dscctf{y0u_4r3_n0w_4_v4l1d_m3mb3r_0f_th3_s3cr3t_gr0up!}
