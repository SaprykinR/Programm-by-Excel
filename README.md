# Programm-by-Excel
LOX=int(input())
LIN=int(input())
LOXLIN=int(input())
MAXLOXEnergy=int(input())
MAXLINEnergy=int(input())
MIXEDEnergy=int(input())
LOXTech=float(input())
LINTech=float(input())
Mode=str(input())
if Mode=="MAXLOX":
    print(LOXTech, "35", "0", (35+0), ((100-LOXTech+35)-LOXTech*0.057), ((50-LINTech+0)-LINTech*0.057), MAXLOXEnergy)
if Mode=="MAXLIN":
    print(LOXTech, "5", "20", (5+20), ((100-LOXTech+5)-LOXTech*0.057), ((50-LINTech+20)-LINTech*0.057), MAXLINEnergy)
if Mode=="MIXED":
    print(LOXTech, "15", "15", (15+15), ((100-LOXTech+15)-LOXTech*0.057), ((50-LINTech+15)-LINTech*0.057), MIXEDEnergy)

    
