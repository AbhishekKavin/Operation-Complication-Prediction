# Operation-Complication-Prediction

Medical complications are the possible things that can go wrong once a surgery is completed and 
there can be multiple cases for a complication as once the patient is out of surgery it doesn't ensure that they are 100% safe. Complications are a as high as 28% in the States.
With all the information provided to us we are trying to predict the possibility of a patient facing a complication so that the doctrs will be ablle to address the issue  




<table class="table">
	  <thead class="thead-dark">
		<tr>
		  <th scope="col">#</th>
		  <th scope="col">Variable</th>
		  <th scope="col">Variable Label</th>
		  <th scope="col">Codes</th>
		</tr>
	  </thead>
	  <tbody>
		<tr>
		  <th scope="row">1</th>
		  <td>ahrq_ccs</td>
		  <td>United States Agency for Healthcare 
Research and Quality’s Clinical 
Classifications Software (AHRQ-CCS) Procedure Category</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">2</th>
		  <td>age</td>
		  <td>Age</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">3</th>
		  <td>gender</td>
		  <td>Gender</td>
		  <td>0 = male; 1 = female</td>
		</tr>
		<tr>
		  <th scope="row">4</th>
		  <td>race</td>
		  <td>Race</td>
		  <td>0 = Caucasian 
1 = African American 
2 = Other</td>
		</tr>
		<tr>
		  <th scope="row">5</th>
		  <td>asa_status</td>
		  <td>American Society of 
Anesthesiologist Physical Status</td>
		  <td>0 = I – II 
1 = III 
2 = IV - VI</td>
		</tr>
		<tr>
		  <th scope="row">6</th>
		  <td>bmi</td>
		  <td>Body Mass Index</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">7</th>
		  <td>baseline_cancer</td>
		  <td>Cancer</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">8</th>
		  <td>baseline_cvd</td>
		  <td>Cardiovascular/Cerebrovascular 
Disease</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">9</th>
		  <td>baseline_dementia</td>
		  <td>Dementia</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">10</th>
		  <td>baseline_diabetes</td>
		  <td>Diabetes</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">11</th>
		  <td>baseline_digestive</td>
		  <td>Digestive Disease</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">12</th>
		  <td>baseline_osteoart</td>
		  <td>Osteoarthritis</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">13</th>
		  <td>baseline_psych</td>
		  <td>Psychiatric Disorder</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">14</th>
		  <td>baseline_pulmonary</td>
		  <td>Pulmonary Disease</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">15</th>
		  <td>baseline_charlson</td>
		  <td>Charlson Comorbidity Index</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">16</th>
		  <td>mortality_rsi</td>
		  <td>Risk Stratification Index (30-Day 
Mortality)</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">17</th>
		  <td>complication_rsi</td>
		  <td>Risk Stratification Index 
(In-Hospital Complications)</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">18</th>
		  <td>ccsMort30Rate</td>
		  <td>Overall Incidence of 30-day 
Mortality for Each AHRQ-CCS 
Procedure Category</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">19</th>
		  <td>ccsComplicationRate</td>
		  <td>Overall incidence of In-Hospital 
Complications for Each AHRQ-CCS Procedure Category</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">20</th>
		  <td>hour</td>
		  <td>Operation Hour</td>
		  <td></td>
		</tr>
		<tr>
		  <th scope="row">21</th>
		  <td>dow</td>
		  <td>Day of Week</td>
		  <td>0 = Monday 
1 = Tuesday 
2 = Wednesday 
3 = Thursday 
4 = Friday</td>
		</tr>
		<tr>
		  <th scope="row">22</th>
		  <td>month</td>
		  <td>Month of Year</td>
		  <td>0 = January 
1 = February 
2 = March 
3 = April 
4 = May 
5 = June 
6 = July 
7 = August 
8 = September 
9 = October 
10 = November 
11 = December</td>
		</tr>
		<tr>
		  <th scope="row">23</th>
		  <td>moonphase</td>
		  <td>Phase of Moon</td>
		  <td>0 = new moon 
1 = first quarter 
2 = full moon 
3 = last quarter</td>
		</tr>
		<tr>
		  <th scope="row">24</th>
		  <td>mort30</td>
		  <td>30-Day Mortality</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
		<tr>
		  <th scope="row">25</th>
		  <td>complication</td>
		  <td>In-Hospital Complication</td>
		  <td>0 = No; 1 = Yes</td>
		</tr>
	  </tbody>
	</table>
