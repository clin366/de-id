De-Id python project

###############Run deid-ChenLin.py######################

python3 deid-ChenLin.py id.text PTname.phi

python3 deid-ChenLin.py id.text age.phi

(Modify the "main" function of deid-ChenLin.py to deid_age(sys.argv[1], sys.argv[2]) )

###############Run stats.py######################

python3 stats.py id.deid id-phi.phrase PTname.phi

python3 stats.py id.deid id-phi.phrase age.phi

