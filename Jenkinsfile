
@Library('snaatak-p7') _

def employeeCI = new org.avengers.template.employeeCI.EmployeeCi()

node {
    
    def url = 'https://github.com/CodeOps-Hub/Employee-API.git'
    def creds = 'vishal-cred'
    def branch = 'feature/employeeCI'
    
    
    employeeCI.call(url, creds, branch)
    
}
