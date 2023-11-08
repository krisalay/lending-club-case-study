# Lending Club Case Study
> This case study aims to give an idea of applying EDA in a real business scenario. In this case study, we will develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

## General Information
<a id="intro"></a>
<h3 >   
      <font color = purple >
            <span style='font-family:Georgia'>
            Introduction:
            </span>   
        </font>    
</h3>
<p>
    <span style='font-family:Georgia'>
    This case study aims to give an idea of applying EDA in a real business scenario. In this case study, we will develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
    </span>
</p>   
<hr>
<h3>
    <font color = purple >
        <span style='font-family:Georgia'>
            Business Understanding:
            </span>   
        </font>    
</h3>
<p>
    <span style='font-family:Georgia'>
    The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a defaulter. Suppose you work for a consumer finance company which specialises in lending various types of loans to urban customers. You have to use EDA to analyse the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected.<br>
        When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
    </span>
</p>
<ul>
    <span style='font-family:Georgia'>
        <li>If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company</li>
        <li>If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.</li>
    </span>
</ul>
    
<p><span style='font-family:Georgia'>The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:</span></p>
<ul>
    <span style='font-family:Georgia'> 
        <li><b>The client with payment difficulties:</b> he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample</li>
        <li><b>All other cases:</b> All other cases when the payment is paid on time</li>
    </span>
</ul>
    
<p><span style='font-family:Georgia'>When a client applies for a loan, there are four types of decisions that could be taken by the client/company):</span></p>

<ol>
    <span style='font-family:Georgia'>
        <li><b>Approved:</b> The Company has approved loan Application</li>
        <li><b>Cancelled:</b> The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.</li>
        <li><b>Refused:</b> The company had rejected the loan (because the client does not meet their requirements etc.)</li>
        <li><b>Unused offer:</b>  Loan has been cancelled by the client but on different stages of the process.</li>
    </span>
</ol>
<hr>
<h3>   
      <font color = purple >
            <span style='font-family:Georgia'>
            Business Objective:
            </span>   
        </font>    
</h3>
<p>
    <span style='font-family:Georgia'>
        This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.<br>
        In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
    </span>
</p>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 36 Months term has less number of defaults
- Loan with grade 'A' has less defaults
- Loan with sub grade ranging from A1 to A5 has less defaults
- The loan taken for marriage, major purchases, credit card, and car has less defaults
- The loan amount requested within range 0 to 14k has less number of defaults
- The applicant's whose annual income is more than 40k has less number of defaults
- Interest rate ranging from 0 to 13% has less number of defaults
- DTI ranging from 0 to 10% has less number of defaults
- People with experience 1 year to 2 years and 8 years to 9 years are less likely to default

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- missingno@0.4.2
- numpy@1.20.3
- matplotlib@3.4.3
- seaborn@0.11.2


## Contributors
- Krisalay
- Sindhushree