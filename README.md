# Quadratic Voting Frontend

此處為[2019總統盃黑客松](https://presidential-hackathon.taiwan.gov.tw/)平方投票法之前端程式碼，供大眾參考利用。

注意：此程式碼不含後端程式碼

This is the frontend code of [Taiwan Presidential Hackathon 2019](https://presidential-hackathon.taiwan.gov.tw/en/Default.aspx) quadratic voting page, and open under MIT License for public use.

Notice: This code did not include backend.

## 投票結果

此處資料為投票後之資料，供大眾研究利用。

### 提案資料

#### 檔案名：

[Proposal.json](data/Proposal.json)

#### 欄位說明：

- ProposalID: 提案編號
- ServiceAgencies: 團體/機構名稱
- TeamName: 隊名
- ProposalTitle: 題目

### 投票結果資料

#### 檔案名：

[ProposalPolls.json](data/ProposalPolls.json)

#### 欄位說明：

- UserID: 使用者編號
- ProposalID: 提案編號
- Count: 得票數
- CreateDate: 建立時間（時區：UTC+8）

### 使用者資料

#### 檔案名：

[User.json](data/User.json)

#### 欄位說明：

- UserID: 使用者編號
- CreateDate: 建立時間（時區：UTC+8）

### 使用者紀錄

#### 檔案名：

[UserAction.json](data/UserAction.json)

#### 欄位說明：

- ActionID: 序號
- UserID: 使用者編號
- ProposalID: 提案編號
- Sequence: 該次投票隨機排序出現在第N位
- Action: 投票或回收
  - Add: 投票
  - Sub: 收回一票
- VoteCount: 投票或收回後剩N票
- SessionID: Session識別碼
- CreateDate: 建立時間（時區：UTC+8）

# Author

陳世祥

# License

[MIT](License)

