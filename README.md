# Loan-System
APIs for a banking system
There are two servers authServer.js and validateToken.js supposed to run on 4000 and 5000 port respectively.

authServer APIs:-
/createUser POST //user signup
/login POST //user login
/custLogin POST //CRM login
/bmLogin POST //BM login
/refreshToken POST //generates new access token and refresh token
/logout DELETE //removes the refresh token from the list

validateToken APIs:-
/applyLoan POST //user applies for loan
/loanList GET //user's list of loans
/loanStatusUpdate POST //CRMs approval for the loans
/loanRequests GET //list of loans assigned to the CRM
/loanUpdateBM POST //BMs approval for the loans
/loanListAll GET //list of all the loans
