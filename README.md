# ICBC_URL_Scheme

1. All URL scheme are tested in iOS 15.
2. Since I don't have any Android devices, I can't test the validity on Android. But it should work. XD


# Examples
According the article from Apple developer [1], URL scheme can be like this:
 
```
# transfer:
com.icbc.iphoneclient://startType=PORTALINJECT&menuId=remit

# account details:
com.icbc.iphoneclient://startType=PORTALINJECT&menuId=account_1

# creditcard details:
com.icbc.iphoneclient://startType=PORTALINJECT&menuId=credit
```


# Scheme Name
```
com.icbc.iphoneclient://
wxe2a19dccf56fd564://
com.icbc.wapbpin://
```

# Parameters  


|   Seq  |   Parameters                                         | Note:|
|-----|---------------------------------------------|----------|
| 3   | MyContactInfo_1                             |
| 7   | account_3                                   |          |
| 8   | account_4_ori                               |          |
| 9   | account_5                                   |          |
| 10  | account_8_more                              |          |
| 11  | account_debitfee_more                       |          |
| 12  | account_lock                                |          |
| 13  | accountthird                                |          |
| 14  | addaccount                                  |          |
| 15  | addedservice_1                              |          |
| 16  | annualaccount                               |          |
| 17  | annuitynew                                  |          |
| 18  | applycredit_1                               |          |
| 19  | applycredit_2                               |          |
| 20  | applycredit_3                               |          |
| 21  | applycredit_4                               |          |
| 22  | applycredit_5                               |          |
| 23  | assetDiagnosis                              |          |
| 24  | autorepay_1                                 |          |
| 25  | autorepay_2                                 |          |
| 26  | bigdeposit_1                                |          |
| 27  | bigdeposit_2                                |          |
| 28  | branchsearch                                |          |
| 29  | cashwithdrawal                              |          |
| 30  | cindividualloanhistoryprint                 |          |
| 31  | cloudProtalNetnode                          |          |
| 32  | code                                        |          |
| 33  | conformity                                  |          |
| 34  | credit                                      |          |
| 35  | credit_1                                    |          |
| 36  | credit_12                                   |          |
| 37  | credit_14                                   |          |
| 38  | credit_15                                   |          |
| 39  | credit_16                                   |          |
| 40  | credit_6                                    |          |
| 41  | credit_7                                    |          |
| 42  | credit_cloudpay                             |          |
| 43  | credit_setting                              |          |
| 44  | creditquickloanlink_1                       |          |
| 45  | creditquickloanlink_2                       |          |
| 46  | creditquickloanlink_3                       |          |
| 47  | currencyexchange                            |          |
| 48  | currencyexchange_3                          |          |
| 49  | currencyexchange_5                          |          |
| 50  | custidentify                                |          |
| 51  | custinfofix                                 |          |
| 52  | deposit                                     |          |
| 53  | digitalcard_upgrade                         |          |
| 54  | digitalcash                                 |          |
| 55  | donation_1                                  |          |
| 56  | eWalletAccount                              |          |
| 57  | ebank_12                                    |          |
| 58  | epay                                        |          |
| 59  | epayDetailList                              |          |
| 60  | epayLimitManage                             |          |
| 61  | epaySafeMange                               |          |
| 62  | epaymentdonation                            |          |
| 63  | exchangesettlement                          |          |
| 64  | faceservice                                 |          |
| 65  | fastbindcard                                |          |
| 66  | favorite                                    |          |
| 67  | finance                                     |          |
| 68  | finance_buy                                 |          |
| 69  | financeproductP_3                           |          |
| 70  | financeproduct_1                            |          |
| 71  | financeproduct_2                            |          |
| 72  | fixcertvalidity                             |          |
| 73  | foreignexchange                             |          |
| 74  | fund_3                                      |          |
| 75  | fund_4                                      |          |
| 76  | fund_8                                      |          |
| 77  | fund_finance                                |          |
| 78  | fund_rn                                     |          |
| 79  | future_4                                    |          |
| 80  | goldStoreNew_2                              |          |
| 81  | icbcgold_allProduct                         |          |
| 82  | icbcwealth                                  |          |
| 83  | insurance                                   |          |
| 84  | insurancesystem                             |          |
| 85  | invest                                      |          |
| 86  | jd_vouchers                                 |          |
| 87  | jiejiegao_1                                 |          |
| 88  | linkageconsumeloan                          |          |
| 89  | loan_merchant_apply                         |          |
| 90  | loanmortgagetaxquery                        |          |
| 91  | loginmanage                                 |          |
| 92  | messenger                                   |          |
| 93  | mine                                        |          |
| 94  | mobile_verify                               |          |
| 95  | mobilenummanage                             |          |
| 96  | mobilenummanage_gray                        |          |
| 97  | myAssetsNew                                 |          |
| 98  | myCashInstallment                           |          |
| 99  | myServiceIM                                 |          |
| 100 | mycreditreport                              |          |
| 101 | mydepositall                                |          |
| 102 | myinsu                                      |          |
| 103 | nationalDebtScoreKeeping_1                  |          |
| 104 | newCitizen                                  |          |
| 105 | nonFungibleToken                            |          |
| 106 | overflowremit                               |          |
| 107 | ovseascustinfo                              |          |
| 108 | paychangesingleformulti_1                   |          |
| 109 | paychangesingleformulti_2                   |          |
| 110 | payment_4                                   |          |
| 111 | payment_5                                   |          |
| 112 | paymentplatform_main                        |          |
| 113 | personal_info                               |          |
| 114 | personalacctsearch                          |          |
| 115 | personalacctsearch_gray                     |          |
| 116 | personalloan                                |          |
| 117 | personalloan_1                              |          |
| 118 | personalloan_11                             |          |
| 119 | personalloan_3                              |          |
| 120 | personalloan_5                              |          |
| 121 | personalloanlement                          |          |
| 122 | preciousmetal                               |          |
| 123 | preciousmetal_1                             |          |
| 124 | preciousmetal_9                             |          |
| 125 | processquery                                |          |
| 126 | quickloancreditandpaychangesingleformulti_2 |          |
| 127 | quotamanage                                 |          |
| 128 | rate                                        |          |
| 129 | receipt_1                                   |          |
| 130 | remit                                       | Transfer |
| 131 | remit_2                                     |          |
| 132 | remit_3                                     |          |
| 133 | remit_appointment                           |          |
| 134 | remitservice_1                              |          |
| 135 | remitservice_2                              |          |
| 136 | reserchgcard                                |          |
| 137 | safe_detection                              |          |
| 138 | safecenter                                  |          |
| 139 | savingbond                                  |          |
| 140 | scanfet                                     |          |
| 141 | securemedia                                 |          |
| 142 | servicecenter                               |          |
| 143 | serviceintegral                             |          |
| 144 | setting                                     |          |
| 145 | setting_1                                   |          |
| 146 | setting_10                                  |          |
| 147 | setting_11                                  |          |
| 148 | setting_16                                  |          |
| 149 | setting_28_new                              |          |
| 150 | setting_35                                  |          |
| 151 | setting_36                                  |          |
| 152 | setting_37                                  |          |
| 153 | setting_42New                               |          |
| 154 | setting_49                                  |          |
| 155 | setting_49_more                             |          |
| 156 | setting_52                                  |          |
| 157 | starlevel                                   |          |
| 158 | stock                                       |          |
| 159 | strucdeposit_list                           |          |
| 160 | subremit_10                                 |          |
| 161 | swallowCard                                 |          |
| 162 | taskCenter                                  |          |
| 163 | thirdpillar                                 |          |
| 164 | timedeposit                                 |          |
| 165 | timedeposit_1                               |          |
| 166 | tinycorpdebt                                |          |
| 167 | tinycorpzone                                |          |
| 168 | ukeyresetpwdmenu                            |          |
| 169 | wealthCommunity                             |          |
| 170 | wxbankunbind                                |          |
| 171 | xinjinyi_1                                  |          |
| 172 | zixinzhengming                              |          |


# Ref
1. https://developer.apple.com/documentation/xcode/defining-a-custom-url-scheme-for-your-app
