
@Library('snaatak-p7') _

def employeeCi = new org.avengers.template.employeeCI.EmployeeCi()

node {
    
    def url = 'https://github.com/CodeOps-Hub/Employee-API.git'
    def branch = 'feature/employeeCI'
    def gitLeaksVersion = '8.18.2'
    def reportName = 'credScanReport.json'
    def depVersion = '9.0.9'
    def javaVersion = '17'
    
    
    employeeCi.call(url, branch, gitLeaksVersion, reportName, depVersion, javaVersion)
    
}
