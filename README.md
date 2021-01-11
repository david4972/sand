# sand

def finance():
           
    print("Welcome to OrgFinance")
    print("What month would you like to budget for ? ")
    A = input()
    if(A == "January".lower()):
            Jan()
    if (A == "Febuary".lower()):
            Feb()
    if(A == "March".lower()):
            Mar()
    if (A == "April".lower()):
            Apr()
    if(A == "May".lower()):
            Ma()
    if (A == "June".lower()):
            Jun()
    if(A == "July".lower()):
            Jul()
    if (A == "August".lower()):
            Aug()
    if(A == "September".lower()):
            Sept()
    if(A == "October".lower()):
            Oct()
    if(A == "November".lower()):
            Nov()
    if(A == "December".lower()):
            Dec()        

    
def Jan():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    January = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    January = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    January = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    January = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    January = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    January = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("January - Transport = {}")
    print(result.format(Transport))
    result = ("January - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("January - Investments = {}")
    print(result.format(Investments))
    result = ("January - Rent = {}")
    print(result.format(Rent))
    result = ("January - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("January - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Jan()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("You have {} remaining from income")
    print(bdg.format(var))
    
def Feb():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    Febuary = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    Febuary = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    Febuary = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    Febuary = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    Febuary = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    Febuary = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("Febuary - Transport = {}")
    print(result.format(Transport))
    result = ("Febuary - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("Febuary - Investments = {}")
    print(result.format(Investments))
    result = ("Febuary - Rent = {}")
    print(result.format(Rent))
    result = ("Febuary - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("Febuary - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Feb()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("You have {} remaining from income")
    print(bdg.format(var))       
    
def Mar():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    March = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    March = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    March = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    March = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    March = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    March = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("March - Transport = {}")
    print(result.format(Transport))
    result = ("March - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("March - Investments = {}")
    print(result.format(Investments))
    result = ("March - Rent = {}")
    print(result.format(Rent))
    result = ("March - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("March - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Mar()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("You have {} remaining from income")
    print(bdg.format(var))
    
def Apr():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    April = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    April = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    April = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    April = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    April = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    April = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("April - Transport = {}")
    print(result.format(Transport))
    result = ("April - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("April - Investments = {}")
    print(result.format(Investments))
    result = ("April - Rent = {}")
    print(result.format(Rent))
    result = ("April - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("April - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Apr()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("You have {} remaining from income")
    print(bdg.format(var))
    
def Ma():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    May = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    May = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    May = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    May = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    May = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    May = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("May - Transport = {}")
    print(result.format(Transport))
    result = ("May - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("May - Investments = {}")
    print(result.format(Investments))
    result = ("May - Rent = {}")
    print(result.format(Rent))
    result = ("May - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("May - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Ma()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("You have {} remaining from income")
    print(bdg.format(var))
        
def Jun():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    June = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    June = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    June = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    June = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    June = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    June = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("June - Transport = {}")
    print(result.format(Transport))
    result = ("June - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("June - Investments = {}")
    print(result.format(Investments))
    result = ("June - Rent = {}")
    print(result.format(Rent))
    result = ("June - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("June - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Jun()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("{} remaining from income")
    print(bdg.format(var))
        
def Jul():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    July = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    July = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    July = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    July = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    July = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    July = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("July - Transport = {}")
    print(result.format(Transport))
    result = ("July - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("July - Investments = {}")
    print(result.format(Investments))
    result = ("July - Rent = {}")
    print(result.format(Rent))
    result = ("July - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("July - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Jul()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("{} remaining from income")
    print(bdg.format(var))
        
def Aug():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    August = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    August = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    August = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    August = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    August = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    August = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("August - Transport = {}")
    print(result.format(Transport))
    result = ("August - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("August - Investments = {}")
    print(result.format(Investments))
    result = ("August - Rent = {}")
    print(result.format(Rent))
    result = ("August - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("August - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Aug()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("{} remaining from income")
    print(bdg.format(var))
    
def Sept():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    September = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    September = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    September = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    September = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    September = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    September = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("September - Transport = {}")
    print(result.format(Transport))
    result = ("September - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("September - Investments = {}")
    print(result.format(Investments))
    result = ("September - Rent = {}")
    print(result.format(Rent))
    result = ("September - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("September - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Sept()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("{} remaining from income")
    print(bdg.format(var))
    
def Oct():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    October = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    October = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    October = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    October = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    October = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    October = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("October - Transport = {}")
    print(result.format(Transport))
    result = ("October - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("October - Investments = {}")
    print(result.format(Investments))
    result = ("October - Rent = {}")
    print(result.format(Rent))
    result = ("October - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("October - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Oct()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("{} remaining from income")
    print(bdg.format(var))
            
def Nov():
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    November = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    November = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    November = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    November = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    November = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    November = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("November - Transport = {}")
    print(result.format(Transport))
    result = ("November - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("November - Investments = {}")
    print(result.format(Investments))
    result = ("November - Rent = {}")
    print(result.format(Rent))
    result = ("November - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("November - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Nov()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("{} remaining from income")
    print(bdg.format(var))
    
def Dec():       
    
    income = 0
    print("What is your Monthly Income after tax ?")
    inc = int(input())
    income+=inc
    i = ("Your Income is {}")
    print(i.format(inc))
    print("How much will you be budgeting for Transport")
    bd = int(input())
    December = Transport = [bd]
    print("How much will you be budgeting for UtilityBills")
    bd = int(input())
    December = UtilityBills = [bd]
    print("How much will you be budgeting for Investments")
    bd = int(input())
    December = Investments = [bd]
    print("How much will you be budgeting for Rent")
    bd = int(input())
    December = Rent = [bd]
    print("How much will you be budgeting for Household Maintenance")
    bd = int(input())
    December = HouseholdMaintenance = [bd]
    print("How much will you be budgeting for Other Expenses")
    bd = int(input())
    December = OtherExpenses = [bd]
    
    mon = ("Income = {}")
    print(mon.format(inc))
    result = ("December - Transport = {}")
    print(result.format(Transport))
    result = ("December - UtilityBills = {}")
    print(result.format(UtilityBills))
    result = ("December - Investments = {}")
    print(result.format(Investments))
    result = ("December - Rent = {}")
    print(result.format(Rent))
    result = ("December - Household Maintenance = {}")
    print(result.format(HouseholdMaintenance))
    result = ("December - Other Expenses = {}")
    print(result.format(OtherExpenses))
    val = Transport[0]+UtilityBills[0]+Investments[0]+Rent[0]+HouseholdMaintenance[0]+OtherExpenses[0]
    if (val > inc):
        print("invalid, you don't have that much money")
        Dec()
    else:
        bud = ("the total budget is {}")
    print(bud.format(val))
    var = inc - val
    bdg = ("{} remaining from income")
    print(bdg.format(var))
            
    
finance()


print("Would you like to budget for another month (Yes or No)")
d = input()
if (d == "Yes".lower()):
    finance()
else:
    exit 
