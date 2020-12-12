# Task-Of-02-12-2020
class hospitamanagmentSystem {
    constructor(patientName,fathername,gender,time,date,contact,nic,patientward,pills,doctorname,doctorfee,addmissonfee,testfee,totalfee,patientcondition){
        this.patientName=patientName
        this.fathername=fathername
        this.gender=gender
        this.time=time
        this.date=date
        this.contact=contact
        this.nic=nic
        this.patientward=patientward
        this.pills=pills
        this.doctorname=doctorname
        this.doctorfee=doctorfee
        this.addmissonfee=addmissonfee
        this.testfee=testfee
        this.totalfee=totalfee
        this.patientcondition=patientcondition
    }
}
class circle extends hospitamanagmentSystem{
    disp(){
        console.log("patientname:"+this.patientName);
        console.log("fathername:"+this.fathername);
        console.log("gender:"+this.gender);
        console.log("time:"+this.time);
        console.log("date:"+this.date);
        console.log("contact:"+this.contact);
        console.log("nic:"+this.nic);
        console.log("patientward:"+this.patientward);
        console.log("pills:"+this.pills);
        console.log("doctorname:"+this.doctorname);
        console.log("doctorfee:"+this.doctorfee);
        console.log("addmissionfee:"+this.addmissonfee);
        console.log("testfee:"+this.testfee);
        console.log("totalfee:"+this.totalfee);
        console.log("patientcondition:"+this.patientcondition);
    }
}
var obj = new circle("xyz","xyz","male","4.00pm","26/05/18","034512121212","42101-78545425-5","heart dieases","heart attack","xyz","5000","10000","30000","45000","sucessfully recover")
obj.disp()
