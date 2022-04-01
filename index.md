## Welcome to GraphEvo Dataset

With the continued evolution of software, there is pressure to maintain a higher level of quality leading to the growing demand for Software Defect Prediction (SDP). Detecting defects in software systems has been an active research area. Researchers have investigated past data and applied various methods for discovering previously unknown bugs and forecasting them. However, most of the past data about software that drives the research are not usually available to the public. Few public datasets exist, but a carefully constructed dataset can be helpful to serve as a benchmark. In this study, we chose 19 open-source Java projects from the publicly available bug dataset, transformed the source code into the graph data, defined a new set of software metrics, including a network portrait metric, and created a public bug database to share with others.
Additionally, we annotated the association between the defects and already-known code elements. We evaluated the credibility of the datasets for 19 open-source Java projects in prediction models. For the validation of the predictive models, we used 13 classification algorithms and obtained F-measure scores ranged from 0.65 to 0.85. We also observed that bugs from different software release coverage were very high (up to 100 percent) for each release.

Projects

<table class="tableizer-table">
   <thead>
      <tr class="tableizer-firstrow">
         <th>Project</th>
         <th>Link</th>
         <th>Domain</th>
         <th>Versions</th>
         <th>#Classes</th>
         <th>kLOC</th>
         <th>#Defects</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>universal-I.L.</td>
         <td><a href="https://github.com/nostra13/Android-Universal-Image-Loader">Link</a></td>
         <td>Android library</td>
         <td>6</td>
         <td>475</td>
         <td>61</td>
         <td>92</td>
      </tr>
      <tr>
         <td>ant</td>
         <td><a href="https://github.com/apache/ant">Link</a></td>
         <td>Build tool</td>
         <td>5</td>
         <td>2078</td>
         <td>474</td>
         <td>767</td>
      </tr>
      <tr>
         <td>antlr</td>
         <td><a href="https://github.com/antlr/antlr4">Link</a></td>
         <td>Language processing</td>
         <td>5</td>
         <td>1696</td>
         <td>382</td>
         <td>45</td>
      </tr>
      <tr>
         <td>broadleafcommerce</td>
         <td><a href="https://github.com/BroadleafCommerce/BroadleafCommerce">Link</a></td>
         <td>E-commerce framework</td>
         <td>8</td>
         <td>2972</td>
         <td>248</td>
         <td>106</td>
      </tr>
      <tr>
         <td>camel</td>
         <td><a href="https://github.com/apache/camel">Link</a></td>
         <td>Enterprise Integration</td>
         <td>2</td>
         <td>623</td>
         <td>52</td>
         <td>463</td>
      </tr>
      <tr>
         <td>hazelcast</td>
         <td><a href="https://github.com/hazelcast/hazelcast">Link</a></td>
         <td>Computing platform</td>
         <td>7</td>
         <td>10279</td>
         <td>107</td>
         <td>2781</td>
      </tr>
      <tr>
         <td>ivy</td>
         <td><a href="https://github.com/apache/ant-ivy">Link</a></td>
         <td>Dependency manager</td>
         <td>2</td>
         <td>564</td>
         <td>91</td>
         <td>91</td>
      </tr>
      <tr>
         <td>junit</td>
         <td><a href="https://github.com/junit-team/junit">Link</a></td>
         <td>Test framework</td>
         <td>8</td>
         <td>1054</td>
         <td>62</td>
         <td>61</td>
      </tr>
      <tr>
         <td>lucene</td>
         <td><a href="https://github.com/apache/lucene">Link</a></td>
         <td>Language processing</td>
         <td>3</td>
         <td>640</td>
         <td>137</td>
         <td>849</td>
      </tr>
      <tr>
         <td>mapdb</td>
         <td><a href="https://github.com/jankotek/MapDB">Link</a></td>
         <td>Database engine</td>
         <td>6</td>
         <td>970</td>
         <td>223</td>
         <td>174</td>
      </tr>
      <tr>
         <td>mcMMO</td>
         <td><a href="https://github.com/mcMMO-Dev/mcMMO">Link</a></td>
         <td>Game</td>
         <td>4</td>
         <td>861</td>
         <td>196</td>
         <td>270</td>
      </tr>
      <tr>
         <td>netty</td>
         <td><a href="https://github.com/netty/netty">Link</a></td>
         <td>Networking framework</td>
         <td>8</td>
         <td>4062</td>
         <td>676</td>
         <td>1027</td>
      </tr>
      <tr>
         <td>orientdb</td>
         <td><a href="https://github.com/orientechnologies/orientdb">Link</a></td>
         <td>Database engine</td>
         <td>3</td>
         <td>2369</td>
         <td>328</td>
         <td>1015</td>
      </tr>
      <tr>
         <td>pbeans</td>
         <td><a href="https://sourceforge.net/projects/pbeans">Link</a></td>
         <td>Language processing</td>
         <td>2</td>
         <td>82</td>
         <td>17</td>
         <td>56</td>
      </tr>
      <tr>
         <td>poi</td>
         <td><a href="https://github.com/apache/poi">Link</a></td>
         <td>Java library</td>
         <td>3</td>
         <td>525</td>
         <td>146</td>
         <td>380</td>
      </tr>
      <tr>
         <td>titan</td>
         <td><a href="https://github.com/thinkaurelius/titan">Link</a></td>
         <td>Database engine</td>
         <td>6</td>
         <td>2997</td>
         <td>318</td>
         <td>203</td>
      </tr>
      <tr>
         <td>velocity</td>
         <td><a href="https://github.com/apache/velocity-engine">Link</a></td>
         <td>Template engine</td>
         <td>3</td>
         <td>428</td>
         <td>125</td>
         <td>92</td>
      </tr>
      <tr>
         <td>xalan</td>
         <td><a href="https://github.com/apache/xalan-java">Link</a></td>
         <td>XSLT processor</td>
         <td>4</td>
         <td>2752</td>
         <td>980</td>
         <td>1441</td>
      </tr>
      <tr>
         <td>xerces</td>
         <td><a href="https://github.com/apache/xerces2-j">Link</a></td>
         <td>XML manipulation</td>
         <td>2</td>
         <td>659</td>
         <td>184</td>
         <td>284</td>
      </tr>
   </tbody>
</table>
          
More Machine learning results

<table class="tableizer-table">
<thead><tr class="tableizer-firstrow"><th>Application</th><th>MLAlgorithm</th><th>MAE</th><th>RMSE</th><th>RAE</th><th>CCInstances</th><th>ICInstances</th><th>F-Measure-NF</th><th>F-Measure-F</th><th>F-Measure</th></tr></thead><tbody>
 <tr><td>antlr</td><td>NaiveBayes</td><td>0.1338</td><td>0.3465</td><td>292.4636</td><td>1468</td><td>220</td><td>0.929</td><td>0.147</td><td>0.911</td></tr>
 <tr><td>antlr</td><td>NaiveBayesMultinomial</td><td>0.3377</td><td>0.5802</td><td>738.2967</td><td>1120</td><td>568</td><td>0.794</td><td>0.087</td><td>0.777</td></tr>
 <tr><td>antlr</td><td>Logistic</td><td>0.0424</td><td>0.1492</td><td>92.7671</td><td>1646</td><td>42</td><td>0.987</td><td>0</td><td>0.965</td></tr>
 <tr><td>antlr</td><td>SGD</td><td>0.0231</td><td>0.152</td><td>50.5129</td><td>1649</td><td>39</td><td>0.988</td><td>?</td><td>?</td></tr>
 <tr><td>antlr</td><td>SimpleLogistic</td><td>0.5</td><td>0.5</td><td>1093.1518</td><td>1649</td><td>39</td><td>0.988</td><td>?</td><td>?</td></tr>
 <tr><td>antlr</td><td>SMO</td><td>0.0231</td><td>0.152</td><td>50.5129</td><td>1649</td><td>39</td><td>0.988</td><td>?</td><td>?</td></tr>
 <tr><td>antlr</td><td>VotedPerceptron</td><td>0.0255</td><td>0.1596</td><td>55.6938</td><td>1645</td><td>43</td><td>0.987</td><td>0</td><td>0.964</td></tr>
 <tr><td>antlr</td><td>DecisonTable</td><td>0.0458</td><td>0.1502</td><td>100.0326</td><td>1649</td><td>39</td><td>0.988</td><td>?</td><td>?</td></tr>
 <tr><td>antlr</td><td>OneR</td><td>0.0243</td><td>0.1558</td><td>53.1033</td><td>1647</td><td>41</td><td>0.988</td><td>0</td><td>0.965</td></tr>
 <tr><td>antlr</td><td>PART</td><td>0.0416</td><td>0.1659</td><td>90.9713</td><td>1639</td><td>49</td><td>0.985</td><td>0.109</td><td>0.965</td></tr>
 <tr><td>antlr</td><td>J48</td><td>0.0448</td><td>0.152</td><td>97.9896</td><td>1647</td><td>41</td><td>0.988</td><td>0</td><td>0.965</td></tr>
 <tr><td>antlr</td><td>RandomForest</td><td>0.0387</td><td>0.1549</td><td>84.5379</td><td>1639</td><td>49</td><td>0.985</td><td>0.075</td><td>0.964</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>NaiveBayes</td><td>0.3758</td><td>0.5343</td><td>182.7944</td><td>294</td><td>174</td><td>0.748</td><td>0.293</td><td>0.695</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>NaiveBayesMultinomial</td><td>0.3622</td><td>0.595</td><td>176.1831</td><td>300</td><td>168</td><td>0.763</td><td>0.263</td><td>0.705</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>Logistic</td><td>0.1643</td><td>0.2958</td><td>79.9403</td><td>415</td><td>53</td><td>0.938</td><td>0.293</td><td>0.864</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>SGD</td><td>0.1175</td><td>0.3428</td><td>57.1713</td><td>413</td><td>55</td><td>0.937</td><td>0.068</td><td>0.837</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>SimpleLogistic</td><td>0.1755</td><td>0.2945</td><td>85.3643</td><td>418</td><td>50</td><td>0.943</td><td>0.219</td><td>0.859</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>SMO</td><td>0.1154</td><td>0.3397</td><td>56.1318</td><td>414</td><td>54</td><td>0.939</td><td>?</td><td>?</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>VotedPerceptron</td><td>0.1345</td><td>0.3666</td><td>65.4378</td><td>405</td><td>63</td><td>0.928</td><td>0</td><td>0.821</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>DecisonTable</td><td>0.2012</td><td>0.3158</td><td>97.8654</td><td>415</td><td>53</td><td>0.94</td><td>0.102</td><td>0.843</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>OneR</td><td>0.1197</td><td>0.3459</td><td>58.2108</td><td>412</td><td>56</td><td>0.936</td><td>0.067</td><td>0.836</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>PART</td><td>0.1575</td><td>0.3207</td><td>76.6419</td><td>405</td><td>63</td><td>0.925</td><td>0.323</td><td>0.856</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>J48</td><td>0.164</td><td>0.3235</td><td>79.7785</td><td>413</td><td>55</td><td>0.936</td><td>0.321</td><td>0.865</td></tr>
 <tr><td>Android-Universal-Image-Loader</td><td>RandomForest</td><td>0.141</td><td>0.2897</td><td>68.5693</td><td>414</td><td>54</td><td>0.936</td><td>0.372</td><td>0.871</td></tr>
 <tr><td>ant</td><td>NaiveBayes</td><td>0.1873</td><td>0.4121</td><td>61.264</td><td>1697</td><td>375</td><td>0.514</td><td>0.889</td><td>0.818</td></tr>
 <tr><td>ant</td><td>NaiveBayesMultinomial</td><td>0.2987</td><td>0.5434</td><td>97.6643</td><td>1453</td><td>619</td><td>0.439</td><td>0.796</td><td>0.729</td></tr>
 <tr><td>ant</td><td>Logistic</td><td>0.2415</td><td>0.3502</td><td>78.9704</td><td>1743</td><td>329</td><td>0.399</td><td>0.909</td><td>0.813</td></tr>
 <tr><td>ant</td><td>SGD</td><td>0.1675</td><td>0.4092</td><td>54.7649</td><td>1725</td><td>347</td><td>0.31</td><td>0.905</td><td>0.793</td></tr>
 <tr><td>ant</td><td>SimpleLogistic</td><td>0.2455</td><td>0.3506</td><td>80.2858</td><td>1734</td><td>338</td><td>0.367</td><td>0.906</td><td>0.805</td></tr>
 <tr><td>ant</td><td>SMO</td><td>0.1752</td><td>0.4186</td><td>57.2901</td><td>1709</td><td>363</td><td>0.206</td><td>0.902</td><td>0.771</td></tr>
 <tr><td>ant</td><td>VotedPerceptron</td><td>0.194</td><td>0.4404</td><td>63.4405</td><td>1670</td><td>402</td><td>0.378</td><td>0.885</td><td>0.79</td></tr>
 <tr><td>ant</td><td>DecisonTable</td><td>0.2395</td><td>0.3477</td><td>78.3251</td><td>1754</td><td>318</td><td>0.474</td><td>0.91</td><td>0.828</td></tr>
 <tr><td>ant</td><td>OneR</td><td>0.1631</td><td>0.4039</td><td>53.3445</td><td>1734</td><td>338</td><td>0.451</td><td>0.904</td><td>0.819</td></tr>
 <tr><td>ant</td><td>PART</td><td>0.223</td><td>0.3587</td><td>72.9169</td><td>1713</td><td>359</td><td>0.331</td><td>0.9</td><td>0.793</td></tr>
 <tr><td>ant</td><td>J48</td><td>0.207</td><td>0.3636</td><td>67.6881</td><td>1750</td><td>322</td><td>0.519</td><td>0.907</td><td>0.834</td></tr>
 <tr><td>ant</td><td>RandomForest</td><td>0.1992</td><td>0.321</td><td>65.1497</td><td>1760</td><td>312</td><td>0.536</td><td>0.91</td><td>0.84</td></tr>
 <tr><td>BroadleafCommerce</td><td>NaiveBayes</td><td>0.1223</td><td>0.3337</td><td>209.2696</td><td>2621</td><td>351</td><td>0.936</td><td>0.17</td><td>0.913</td></tr>
 <tr><td>BroadleafCommerce</td><td>NaiveBayesMultinomial</td><td>0.3213</td><td>0.5652</td><td>549.9751</td><td>2018</td><td>954</td><td>0.804</td><td>0.117</td><td>0.783</td></tr>
 <tr><td>BroadleafCommerce</td><td>Logistic</td><td>0.0543</td><td>0.166</td><td>92.9766</td><td>2883</td><td>89</td><td>0.985</td><td>?</td><td>?</td></tr>
 <tr><td>BroadleafCommerce</td><td>SGD</td><td>0.0299</td><td>0.173</td><td>51.2521</td><td>2883</td><td>89</td><td>0.985</td><td>?</td><td>?</td></tr>
 <tr><td>BroadleafCommerce</td><td>SimpleLogistic</td><td>0.1181</td><td>0.2261</td><td>202.1261</td><td>2883</td><td>89</td><td>0.985</td><td>?</td><td>?</td></tr>
 <tr><td>BroadleafCommerce</td><td>SMO</td><td>0.0299</td><td>0.173</td><td>51.2521</td><td>2883</td><td>89</td><td>0.985</td><td>?</td><td>?</td></tr>
 <tr><td>BroadleafCommerce</td><td>VotedPerceptron</td><td>0.0299</td><td>0.173</td><td>51.2521</td><td>2883</td><td>89</td><td>0.985</td><td>?</td><td>?</td></tr>
 <tr><td>BroadleafCommerce</td><td>DecisonTable</td><td>0.0583</td><td>0.1705</td><td>99.77</td><td>2883</td><td>89</td><td>0.985</td><td>?</td><td>?</td></tr>
 <tr><td>BroadleafCommerce</td><td>OneR</td><td>0.031</td><td>0.1759</td><td>52.9797</td><td>2880</td><td>92</td><td>0.984</td><td>0</td><td>0.955</td></tr>
 <tr><td>BroadleafCommerce</td><td>PART</td><td>0.0484</td><td>0.1736</td><td>82.9087</td><td>2878</td><td>94</td><td>0.984</td><td>0.217</td><td>0.961</td></tr>
 <tr><td>BroadleafCommerce</td><td>J48</td><td>0.0523</td><td>0.167</td><td>89.5038</td><td>2886</td><td>86</td><td>0.985</td><td>0.122</td><td>0.959</td></tr>
 <tr><td>BroadleafCommerce</td><td>RandomForest</td><td>0.0474</td><td>0.1662</td><td>81.1338</td><td>2875</td><td>97</td><td>0.983</td><td>0.142</td><td>0.958</td></tr>
 <tr><td>camel</td><td>NaiveBayes</td><td>0.3924</td><td>0.5521</td><td>91.4543</td><td>397</td><td>226</td><td>0.756</td><td>0.294</td><td>0.612</td></tr>
 <tr><td>camel</td><td>NaiveBayesMultinomial</td><td>0.4571</td><td>0.663</td><td>106.5314</td><td>341</td><td>282</td><td>0.657</td><td>0.335</td><td>0.557</td></tr>
 <tr><td>camel</td><td>Logistic</td><td>0.4146</td><td>0.4642</td><td>96.622</td><td>417</td><td>206</td><td>0.798</td><td>0.088</td><td>0.577</td></tr>
 <tr><td>camel</td><td>SGD</td><td>0.313</td><td>0.5595</td><td>72.9408</td><td>428</td><td>195</td><td>0.814</td><td>0</td><td>0.561</td></tr>
 <tr><td>camel</td><td>SimpleLogistic</td><td>0.488</td><td>0.4954</td><td>113.7151</td><td>425</td><td>198</td><td>0.811</td><td>0.01</td><td>0.561</td></tr>
 <tr><td>camel</td><td>SMO</td><td>0.3114</td><td>0.558</td><td>72.5667</td><td>429</td><td>194</td><td>0.816</td><td>?</td><td>?</td></tr>
 <tr><td>camel</td><td>VotedPerceptron</td><td>0.329</td><td>0.5735</td><td>76.6638</td><td>418</td><td>205</td><td>0.8</td><td>0.072</td><td>0.573</td></tr>
 <tr><td>camel</td><td>DecisonTable</td><td>0.4292</td><td>0.4631</td><td>100.0175</td><td>429</td><td>194</td><td>0.816</td><td>?</td><td>?</td></tr>
 <tr><td>camel</td><td>OneR</td><td>0.3419</td><td>0.5847</td><td>79.6738</td><td>410</td><td>213</td><td>0.773</td><td>0.311</td><td>0.629</td></tr>
 <tr><td>camel</td><td>PART</td><td>0.4043</td><td>0.4667</td><td>94.2157</td><td>428</td><td>195</td><td>0.812</td><td>0.076</td><td>0.582</td></tr>
 <tr><td>camel</td><td>J48</td><td>0.3834</td><td>0.4901</td><td>89.3454</td><td>430</td><td>193</td><td>0.799</td><td>0.323</td><td>0.651</td></tr>
 <tr><td>camel</td><td>RandomForest</td><td>0.3555</td><td>0.441</td><td>82.8442</td><td>444</td><td>179</td><td>0.807</td><td>0.435</td><td>0.691</td></tr>
 <tr><td>hazelcast</td><td>NaiveBayes</td><td>0.1377</td><td>0.354</td><td>77.1845</td><td>8917</td><td>1361</td><td>0.927</td><td>0.248</td><td>0.86</td></tr>
 <tr><td>hazelcast</td><td>NaiveBayesMultinomial</td><td>0.342</td><td>0.5803</td><td>191.7297</td><td>6791</td><td>3487</td><td>0.784</td><td>0.211</td><td>0.727</td></tr>
 <tr><td>hazelcast</td><td>Logistic</td><td>0.1644</td><td>0.2878</td><td>92.1527</td><td>9265</td><td>1013</td><td>0.948</td><td>0.078</td><td>0.862</td></tr>
 <tr><td>hazelcast</td><td>SGD</td><td>0.0989</td><td>0.3146</td><td>55.4691</td><td>9261</td><td>1017</td><td>0.948</td><td>?</td><td>?</td></tr>
 <tr><td>hazelcast</td><td>SimpleLogistic</td><td>0.1785</td><td>0.2905</td><td>100.0663</td><td>9267</td><td>1011</td><td>0.948</td><td>0.063</td><td>0.861</td></tr>
 <tr><td>hazelcast</td><td>SMO</td><td>0.0989</td><td>0.3146</td><td>55.4691</td><td>9261</td><td>1017</td><td>0.948</td><td>?</td><td>?</td></tr>
 <tr><td>hazelcast</td><td>VotedPerceptron</td><td>0.1113</td><td>0.3336</td><td>62.396</td><td>9134</td><td>1144</td><td>0.941</td><td>0.071</td><td>0.855</td></tr>
 <tr><td>hazelcast</td><td>DecisonTable</td><td>0.167</td><td>0.2854</td><td>93.6372</td><td>9292</td><td>986</td><td>0.949</td><td>0.177</td><td>0.873</td></tr>
 <tr><td>hazelcast</td><td>OneR</td><td>0.1011</td><td>0.3179</td><td>56.6691</td><td>9239</td><td>1039</td><td>0.946</td><td>0.099</td><td>0.863</td></tr>
 <tr><td>hazelcast</td><td>PART</td><td>0.1329</td><td>0.2701</td><td>74.517</td><td>9321</td><td>957</td><td>0.95</td><td>0.283</td><td>0.884</td></tr>
 <tr><td>hazelcast</td><td>J48</td><td>0.1267</td><td>0.2808</td><td>71.0382</td><td>9329</td><td>949</td><td>0.95</td><td>0.422</td><td>0.898</td></tr>
 <tr><td>hazelcast</td><td>RandomForest</td><td>0.1104</td><td>0.2461</td><td>61.8969</td><td>9433</td><td>845</td><td>0.955</td><td>0.496</td><td>0.91</td></tr>
 <tr><td>ivy</td><td>NaiveBayes</td><td>0.1472</td><td>0.3735</td><td>80.4429</td><td>475</td><td>79</td><td>0.921</td><td>0.301</td><td>0.858</td></tr>
 <tr><td>ivy</td><td>NaiveBayesMultinomial</td><td>0.297</td><td>0.5425</td><td>162.2915</td><td>391</td><td>163</td><td>0.817</td><td>0.249</td><td>0.76</td></tr>
 <tr><td>ivy</td><td>Logistic</td><td>0.1658</td><td>0.3048</td><td>90.6159</td><td>492</td><td>62</td><td>0.94</td><td>0.162</td><td>0.861</td></tr>
 <tr><td>ivy</td><td>SGD</td><td>0.1047</td><td>0.3236</td><td>57.2053</td><td>496</td><td>58</td><td>0.945</td><td>0</td><td>0.849</td></tr>
 <tr><td>ivy</td><td>SimpleLogistic</td><td>0.276</td><td>0.3696</td><td>150.8064</td><td>496</td><td>58</td><td>0.945</td><td>0.065</td><td>0.856</td></tr>
 <tr><td>ivy</td><td>SMO</td><td>0.1029</td><td>0.3208</td><td>56.219</td><td>497</td><td>57</td><td>0.946</td><td>0</td><td>0.85</td></tr>
 <tr><td>ivy</td><td>VotedPerceptron</td><td>0.1101</td><td>0.3318</td><td>60.1643</td><td>493</td><td>61</td><td>0.941</td><td>0.116</td><td>0.858</td></tr>
 <tr><td>ivy</td><td>DecisonTable</td><td>0.1737</td><td>0.3057</td><td>94.8912</td><td>492</td><td>62</td><td>0.94</td><td>0.061</td><td>0.852</td></tr>
 <tr><td>ivy</td><td>OneR</td><td>0.1191</td><td>0.3452</td><td>65.0957</td><td>488</td><td>66</td><td>0.936</td><td>0.083</td><td>0.85</td></tr>
 <tr><td>ivy</td><td>PART</td><td>0.1381</td><td>0.3091</td><td>75.4592</td><td>496</td><td>58</td><td>0.943</td><td>0.326</td><td>0.881</td></tr>
 <tr><td>ivy</td><td>J48</td><td>0.1461</td><td>0.3121</td><td>79.8338</td><td>492</td><td>62</td><td>0.939</td><td>0.311</td><td>0.876</td></tr>
 <tr><td>ivy</td><td>RandomForest</td><td>0.1488</td><td>0.2808</td><td>81.2908</td><td>498</td><td>56</td><td>0.946</td><td>0.282</td><td>0.879</td></tr>
 <tr><td>junit</td><td>NaiveBayes</td><td>0.1609</td><td>0.3355</td><td>186.7695</td><td>920</td><td>133</td><td>0.932</td><td>0.119</td><td>0.896</td></tr>
 <tr><td>junit</td><td>NaiveBayesMultinomial</td><td>0.261</td><td>0.5002</td><td>302.9793</td><td>779</td><td>274</td><td>0.848</td><td>0.099</td><td>0.815</td></tr>
 <tr><td>junit</td><td>Logistic</td><td>0.0817</td><td>0.2038</td><td>94.8389</td><td>1006</td><td>47</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>junit</td><td>SGD</td><td>0.0446</td><td>0.2113</td><td>51.8035</td><td>1006</td><td>47</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>junit</td><td>SimpleLogistic</td><td>0.5</td><td>0.5</td><td>580.3097</td><td>1006</td><td>47</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>junit</td><td>SMO</td><td>0.0446</td><td>0.2113</td><td>51.8035</td><td>1006</td><td>47</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>junit</td><td>VotedPerceptron</td><td>0.0446</td><td>0.2113</td><td>51.8035</td><td>1006</td><td>47</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>junit</td><td>DecisonTable</td><td>0.0861</td><td>0.2065</td><td>99.9392</td><td>1006</td><td>47</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>junit</td><td>OneR</td><td>0.0475</td><td>0.2179</td><td>55.1101</td><td>1003</td><td>50</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>junit</td><td>PART</td><td>0.0634</td><td>0.2027</td><td>73.6153</td><td>1007</td><td>46</td><td>0.977</td><td>0.41</td><td>0.952</td></tr>
 <tr><td>junit</td><td>J48</td><td>0.0655</td><td>0.1881</td><td>76.0436</td><td>1013</td><td>40</td><td>0.98</td><td>0.355</td><td>0.953</td></tr>
 <tr><td>junit</td><td>RandomForest</td><td>0.0487</td><td>0.1614</td><td>56.5594</td><td>1019</td><td>34</td><td>0.983</td><td>0.564</td><td>0.965</td></tr>
 <tr><td>lucene</td><td>NaiveBayes</td><td>0.3427</td><td>0.5636</td><td>69.8842</td><td>418</td><td>214</td><td>0.746</td><td>0.49</td><td>0.636</td></tr>
 <tr><td>lucene</td><td>NaiveBayesMultinomial</td><td>0.3767</td><td>0.6039</td><td>76.8159</td><td>386</td><td>246</td><td>0.657</td><td>0.549</td><td>0.611</td></tr>
 <tr><td>lucene</td><td>Logistic</td><td>0.4051</td><td>0.4604</td><td>82.6257</td><td>437</td><td>195</td><td>0.751</td><td>0.595</td><td>0.684</td></tr>
 <tr><td>lucene</td><td>SGD</td><td>0.3497</td><td>0.5913</td><td>71.3141</td><td>411</td><td>221</td><td>0.737</td><td>0.478</td><td>0.625</td></tr>
 <tr><td>lucene</td><td>SimpleLogistic</td><td>0.4086</td><td>0.4576</td><td>83.3282</td><td>425</td><td>207</td><td>0.736</td><td>0.57</td><td>0.664</td></tr>
 <tr><td>lucene</td><td>SMO</td><td>0.3418</td><td>0.5846</td><td>69.7007</td><td>416</td><td>216</td><td>0.744</td><td>0.486</td><td>0.633</td></tr>
 <tr><td>lucene</td><td>VotedPerceptron</td><td>0.3284</td><td>0.5726</td><td>66.9769</td><td>424</td><td>208</td><td>0.742</td><td>0.546</td><td>0.658</td></tr>
 <tr><td>lucene</td><td>DecisonTable</td><td>0.3903</td><td>0.4464</td><td>79.6049</td><td>452</td><td>180</td><td>0.767</td><td>0.634</td><td>0.71</td></tr>
 <tr><td>lucene</td><td>OneR</td><td>0.3639</td><td>0.6033</td><td>74.2183</td><td>402</td><td>230</td><td>0.697</td><td>0.545</td><td>0.632</td></tr>
 <tr><td>lucene</td><td>PART</td><td>0.329</td><td>0.4714</td><td>67.0917</td><td>449</td><td>183</td><td>0.754</td><td>0.649</td><td>0.709</td></tr>
 <tr><td>lucene</td><td>J48</td><td>0.3428</td><td>0.4867</td><td>69.9072</td><td>446</td><td>186</td><td>0.748</td><td>0.646</td><td>0.704</td></tr>
 <tr><td>lucene</td><td>RandomForest</td><td>0.3138</td><td>0.4159</td><td>63.9943</td><td>463</td><td>169</td><td>0.771</td><td>0.678</td><td>0.731</td></tr>
 <tr><td>mapdb</td><td>NaiveBayes</td><td>0.1579</td><td>0.3864</td><td>87.2615</td><td>818</td><td>151</td><td>0.249</td><td>0.913</td><td>0.847</td></tr>
 <tr><td>mapdb</td><td>NaiveBayesMultinomial</td><td>0.3306</td><td>0.5739</td><td>182.7524</td><td>648</td><td>321</td><td>0.203</td><td>0.791</td><td>0.732</td></tr>
 <tr><td>mapdb</td><td>Logistic</td><td>0.158</td><td>0.2877</td><td>87.3221</td><td>872</td><td>97</td><td>0.211</td><td>0.947</td><td>0.873</td></tr>
 <tr><td>mapdb</td><td>SGD</td><td>0.1011</td><td>0.318</td><td>55.9064</td><td>871</td><td>98</td><td>0.155</td><td>0.946</td><td>0.867</td></tr>
 <tr><td>mapdb</td><td>SimpleLogistic</td><td>0.188</td><td>0.2976</td><td>103.9168</td><td>866</td><td>103</td><td>0.088</td><td>0.944</td><td>0.858</td></tr>
 <tr><td>mapdb</td><td>SMO</td><td>0.1042</td><td>0.3228</td><td>57.6178</td><td>868</td><td>101</td><td>0.106</td><td>0.945</td><td>0.861</td></tr>
 <tr><td>mapdb</td><td>VotedPerceptron</td><td>0.1011</td><td>0.318</td><td>55.9064</td><td>871</td><td>98</td><td>0</td><td>0.947</td><td>0.852</td></tr>
 <tr><td>mapdb</td><td>DecisonTable</td><td>0.1742</td><td>0.2974</td><td>96.2823</td><td>865</td><td>104</td><td>0.088</td><td>0.943</td><td>0.857</td></tr>
 <tr><td>mapdb</td><td>OneR</td><td>0.1146</td><td>0.3385</td><td>63.3226</td><td>858</td><td>111</td><td>0.018</td><td>0.939</td><td>0.847</td></tr>
 <tr><td>mapdb</td><td>PART</td><td>0.1524</td><td>0.3169</td><td>84.2714</td><td>854</td><td>115</td><td>0.161</td><td>0.936</td><td>0.859</td></tr>
 <tr><td>mapdb</td><td>J48</td><td>0.1643</td><td>0.3154</td><td>90.7972</td><td>858</td><td>111</td><td>0.112</td><td>0.939</td><td>0.856</td></tr>
 <tr><td>mapdb</td><td>RandomForest</td><td>0.1269</td><td>0.2739</td><td>70.1248</td><td>863</td><td>106</td><td>0.312</td><td>0.941</td><td>0.878</td></tr>
 <tr><td>mcMMO</td><td>NaiveBayes</td><td>0.2231</td><td>0.4183</td><td>99.6925</td><td>687</td><td>173</td><td>0.882</td><td>0.311</td><td>0.809</td></tr>
 <tr><td>mcMMO</td><td>NaiveBayesMultinomial</td><td>0.3773</td><td>0.6127</td><td>168.5635</td><td>535</td><td>325</td><td>0.746</td><td>0.263</td><td>0.684</td></tr>
 <tr><td>mcMMO</td><td>Logistic</td><td>0.2032</td><td>0.3276</td><td>90.7766</td><td>741</td><td>119</td><td>0.925</td><td>0.131</td><td>0.823</td></tr>
 <tr><td>mcMMO</td><td>SGD</td><td>0.1279</td><td>0.3576</td><td>57.1505</td><td>750</td><td>110</td><td>0.932</td><td>?</td><td>?</td></tr>
 <tr><td>mcMMO</td><td>SimpleLogistic</td><td>0.3766</td><td>0.4244</td><td>168.2574</td><td>750</td><td>110</td><td>0.932</td><td>0.035</td><td>0.817</td></tr>
 <tr><td>mcMMO</td><td>SMO</td><td>0.1279</td><td>0.3576</td><td>57.1505</td><td>750</td><td>110</td><td>0.932</td><td>?</td><td>?</td></tr>
 <tr><td>mcMMO</td><td>VotedPerceptron</td><td>0.1372</td><td>0.3704</td><td>61.3069</td><td>742</td><td>118</td><td>0.926</td><td>0.017</td><td>0.81</td></tr>
 <tr><td>mcMMO</td><td>DecisonTable</td><td>0.2238</td><td>0.334</td><td>100.0124</td><td>750</td><td>110</td><td>0.932</td><td>?</td><td>?</td></tr>
 <tr><td>mcMMO</td><td>OneR</td><td>0.1419</td><td>0.3766</td><td>63.3851</td><td>738</td><td>122</td><td>0.923</td><td>0.032</td><td>0.809</td></tr>
 <tr><td>mcMMO</td><td>PART</td><td>0.2119</td><td>0.3339</td><td>94.6918</td><td>747</td><td>113</td><td>0.929</td><td>0.096</td><td>0.823</td></tr>
 <tr><td>mcMMO</td><td>J48</td><td>0.2172</td><td>0.3394</td><td>97.0372</td><td>744</td><td>116</td><td>0.927</td><td>0.079</td><td>0.819</td></tr>
 <tr><td>mcMMO</td><td>RandomForest</td><td>0.1966</td><td>0.3525</td><td>87.8319</td><td>712</td><td>148</td><td>0.904</td><td>0.178</td><td>0.811</td></tr>
 <tr><td>netty</td><td>NaiveBayes</td><td>0.3683</td><td>0.4891</td><td>208.5871</td><td>2622</td><td>1419</td><td>0.766</td><td>0.295</td><td>0.72</td></tr>
 <tr><td>netty</td><td>NaiveBayesMultinomial</td><td>0.22</td><td>0.4627</td><td>124.5763</td><td>3161</td><td>880</td><td>0.876</td><td>0.081</td><td>0.799</td></tr>
 <tr><td>netty</td><td>Logistic</td><td>0.151</td><td>0.2751</td><td>85.5407</td><td>3644</td><td>397</td><td>0.948</td><td>0.029</td><td>0.858</td></tr>
 <tr><td>netty</td><td>SGD</td><td>0.0977</td><td>0.3126</td><td>55.361</td><td>3646</td><td>395</td><td>0.949</td><td>?</td><td>?</td></tr>
 <tr><td>netty</td><td>SimpleLogistic</td><td>0.1881</td><td>0.3051</td><td>106.5348</td><td>3647</td><td>394</td><td>0.949</td><td>0.015</td><td>0.857</td></tr>
 <tr><td>netty</td><td>SMO</td><td>0.0977</td><td>0.3126</td><td>55.361</td><td>3646</td><td>395</td><td>0.949</td><td>?</td><td>?</td></tr>
 <tr><td>netty</td><td>VotedPerceptron</td><td>0.1057</td><td>0.3251</td><td>59.8459</td><td>3614</td><td>427</td><td>0.944</td><td>0</td><td>0.852</td></tr>
 <tr><td>netty</td><td>DecisonTable</td><td>0.1679</td><td>0.2873</td><td>95.1061</td><td>3651</td><td>390</td><td>0.949</td><td>0.025</td><td>0.859</td></tr>
 <tr><td>netty</td><td>OneR</td><td>0.1</td><td>0.3162</td><td>56.6224</td><td>3637</td><td>404</td><td>0.947</td><td>0.126</td><td>0.867</td></tr>
 <tr><td>netty</td><td>PART</td><td>0.1147</td><td>0.2674</td><td>64.9385</td><td>3690</td><td>351</td><td>0.953</td><td>0.478</td><td>0.906</td></tr>
 <tr><td>netty</td><td>J48</td><td>0.111</td><td>0.2579</td><td>62.8828</td><td>3743</td><td>298</td><td>0.96</td><td>0.522</td><td>0.917</td></tr>
 <tr><td>netty</td><td>RandomForest</td><td>0.0905</td><td>0.2226</td><td>51.2589</td><td>3786</td><td>255</td><td>0.965</td><td>0.631</td><td>0.933</td></tr>
 <tr><td>orientdb</td><td>NaiveBayes</td><td>0.3559</td><td>0.4592</td><td>113.4096</td><td>1661</td><td>686</td><td>0.794</td><td>0.495</td><td>0.736</td></tr>
 <tr><td>orientdb</td><td>NaiveBayesMultinomial</td><td>0.4113</td><td>0.6202</td><td>131.0874</td><td>1388</td><td>959</td><td>0.714</td><td>0.285</td><td>0.63</td></tr>
 <tr><td>orientdb</td><td>Logistic</td><td>0.2414</td><td>0.3509</td><td>76.9351</td><td>1884</td><td>463</td><td>0.883</td><td>0.367</td><td>0.783</td></tr>
 <tr><td>orientdb</td><td>SGD</td><td>0.1947</td><td>0.4413</td><td>62.055</td><td>1890</td><td>457</td><td>0.892</td><td>?</td><td>?</td></tr>
 <tr><td>orientdb</td><td>SimpleLogistic</td><td>0.262</td><td>0.3568</td><td>83.5094</td><td>1894</td><td>453</td><td>0.89</td><td>0.207</td><td>0.757</td></tr>
 <tr><td>orientdb</td><td>SMO</td><td>0.1947</td><td>0.4413</td><td>62.055</td><td>1890</td><td>457</td><td>0.892</td><td>?</td><td>?</td></tr>
 <tr><td>orientdb</td><td>VotedPerceptron</td><td>0.1951</td><td>0.4417</td><td>62.1908</td><td>1889</td><td>458</td><td>0.892</td><td>0</td><td>0.718</td></tr>
 <tr><td>orientdb</td><td>DecisonTable</td><td>0.247</td><td>0.3396</td><td>78.7225</td><td>1994</td><td>353</td><td>0.91</td><td>0.539</td><td>0.838</td></tr>
 <tr><td>orientdb</td><td>OneR</td><td>0.1798</td><td>0.424</td><td>57.3024</td><td>1925</td><td>422</td><td>0.895</td><td>0.372</td><td>0.793</td></tr>
 <tr><td>orientdb</td><td>PART</td><td>0.188</td><td>0.3297</td><td>59.9135</td><td>1986</td><td>361</td><td>0.908</td><td>0.534</td><td>0.835</td></tr>
 <tr><td>orientdb</td><td>J48</td><td>0.1646</td><td>0.316</td><td>52.4642</td><td>2053</td><td>294</td><td>0.924</td><td>0.634</td><td>0.868</td></tr>
 <tr><td>orientdb</td><td>RandomForest</td><td>0.1488</td><td>0.2878</td><td>47.4166</td><td>2083</td><td>264</td><td>0.931</td><td>0.701</td><td>0.886</td></tr>
 <tr><td>pbeans</td><td>NaiveBayes</td><td>0.2994</td><td>0.5262</td><td>66.6234</td><td>56</td><td>24</td><td>0.429</td><td>0.797</td><td>0.672</td></tr>
 <tr><td>pbeans</td><td>NaiveBayesMultinomial</td><td>0.2749</td><td>0.5226</td><td>61.1792</td><td>58</td><td>22</td><td>0.542</td><td>0.804</td><td>0.715</td></tr>
 <tr><td>pbeans</td><td>Logistic</td><td>0.2998</td><td>0.4826</td><td>66.7139</td><td>57</td><td>23</td><td>0.566</td><td>0.785</td><td>0.711</td></tr>
 <tr><td>pbeans</td><td>SGD</td><td>0.3125</td><td>0.559</td><td>69.5489</td><td>55</td><td>25</td><td>0.419</td><td>0.786</td><td>0.662</td></tr>
 <tr><td>pbeans</td><td>SimpleLogistic</td><td>0.347</td><td>0.4596</td><td>77.2271</td><td>55</td><td>25</td><td>0.49</td><td>0.775</td><td>0.679</td></tr>
 <tr><td>pbeans</td><td>SMO</td><td>0.3</td><td>0.5477</td><td>66.7669</td><td>56</td><td>24</td><td>0.368</td><td>0.803</td><td>0.657</td></tr>
 <tr><td>pbeans</td><td>VotedPerceptron</td><td>0.2798</td><td>0.5247</td><td>62.2621</td><td>57</td><td>23</td><td>0.582</td><td>0.781</td><td>0.714</td></tr>
 <tr><td>pbeans</td><td>DecisonTable</td><td>0.3148</td><td>0.4074</td><td>70.0681</td><td>61</td><td>19</td><td>0.667</td><td>0.816</td><td>0.765</td></tr>
 <tr><td>pbeans</td><td>OneR</td><td>0.1875</td><td>0.433</td><td>41.7293</td><td>65</td><td>15</td><td>0.681</td><td>0.867</td><td>0.804</td></tr>
 <tr><td>pbeans</td><td>PART</td><td>0.3219</td><td>0.505</td><td>71.6416</td><td>55</td><td>25</td><td>0.468</td><td>0.779</td><td>0.674</td></tr>
 <tr><td>pbeans</td><td>J48</td><td>0.3413</td><td>0.5045</td><td>75.9679</td><td>54</td><td>26</td><td>0.5</td><td>0.759</td><td>0.672</td></tr>
 <tr><td>pbeans</td><td>RandomForest</td><td>0.3199</td><td>0.4139</td><td>71.1922</td><td>59</td><td>21</td><td>0.588</td><td>0.807</td><td>0.733</td></tr>
 <tr><td>poi</td><td>NaiveBayes</td><td>0.2907</td><td>0.5261</td><td>65.3782</td><td>367</td><td>149</td><td>0.811</td><td>0.392</td><td>0.671</td></tr>
 <tr><td>poi</td><td>NaiveBayesMultinomial</td><td>0.3279</td><td>0.569</td><td>73.7368</td><td>346</td><td>170</td><td>0.735</td><td>0.564</td><td>0.678</td></tr>
 <tr><td>poi</td><td>Logistic</td><td>0.3559</td><td>0.4336</td><td>80.0438</td><td>377</td><td>139</td><td>0.815</td><td>0.505</td><td>0.712</td></tr>
 <tr><td>poi</td><td>SGD</td><td>0.2752</td><td>0.5246</td><td>61.8839</td><td>374</td><td>142</td><td>0.808</td><td>0.514</td><td>0.71</td></tr>
 <tr><td>poi</td><td>SimpleLogistic</td><td>0.3542</td><td>0.4244</td><td>79.6443</td><td>383</td><td>133</td><td>0.824</td><td>0.52</td><td>0.723</td></tr>
 <tr><td>poi</td><td>SMO</td><td>0.2791</td><td>0.5283</td><td>62.7555</td><td>372</td><td>144</td><td>0.806</td><td>0.503</td><td>0.705</td></tr>
 <tr><td>poi</td><td>VotedPerceptron</td><td>0.3314</td><td>0.5746</td><td>74.5148</td><td>345</td><td>171</td><td>0.758</td><td>0.474</td><td>0.663</td></tr>
 <tr><td>poi</td><td>DecisonTable</td><td>0.3725</td><td>0.4473</td><td>83.7705</td><td>361</td><td>155</td><td>0.788</td><td>0.485</td><td>0.687</td></tr>
 <tr><td>poi</td><td>OneR</td><td>0.345</td><td>0.5873</td><td>77.5728</td><td>338</td><td>178</td><td>0.766</td><td>0.341</td><td>0.625</td></tr>
 <tr><td>poi</td><td>PART</td><td>0.337</td><td>0.4751</td><td>75.7907</td><td>374</td><td>142</td><td>0.802</td><td>0.551</td><td>0.718</td></tr>
 <tr><td>poi</td><td>J48</td><td>0.3387</td><td>0.5019</td><td>76.162</td><td>367</td><td>149</td><td>0.79</td><td>0.539</td><td>0.706</td></tr>
 <tr><td>poi</td><td>RandomForest</td><td>0.3281</td><td>0.4357</td><td>73.7728</td><td>359</td><td>157</td><td>0.782</td><td>0.495</td><td>0.687</td></tr>
 <tr><td>titan</td><td>NaiveBayes</td><td>0.1061</td><td>0.3046</td><td>121.5577</td><td>2689</td><td>297</td><td>0.947</td><td>0.134</td><td>0.91</td></tr>
 <tr><td>titan</td><td>NaiveBayesMultinomial</td><td>0.3958</td><td>0.6217</td><td>453.5881</td><td>1813</td><td>1173</td><td>0.751</td><td>0.068</td><td>0.72</td></tr>
 <tr><td>titan</td><td>Logistic</td><td>0.0839</td><td>0.2073</td><td>96.1685</td><td>2847</td><td>139</td><td>0.976</td><td>0</td><td>0.932</td></tr>
 <tr><td>titan</td><td>SGD</td><td>0.0455</td><td>0.2134</td><td>52.2014</td><td>2850</td><td>136</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>titan</td><td>SimpleLogistic</td><td>0.5</td><td>0.5</td><td>573.0637</td><td>2850</td><td>136</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>titan</td><td>SMO</td><td>0.0455</td><td>0.2134</td><td>52.2014</td><td>2850</td><td>136</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>titan</td><td>VotedPerceptron</td><td>0.0479</td><td>0.2188</td><td>54.8882</td><td>2843</td><td>143</td><td>0.975</td><td>0</td><td>0.931</td></tr>
 <tr><td>titan</td><td>DecisonTable</td><td>0.0873</td><td>0.2085</td><td>100.076</td><td>2850</td><td>136</td><td>0.977</td><td>?</td><td>?</td></tr>
 <tr><td>titan</td><td>OneR</td><td>0.0442</td><td>0.2103</td><td>50.666</td><td>2854</td><td>132</td><td>0.977</td><td>0.12</td><td>0.938</td></tr>
 <tr><td>titan</td><td>PART</td><td>0.0789</td><td>0.2066</td><td>90.3996</td><td>2845</td><td>141</td><td>0.976</td><td>0.041</td><td>0.933</td></tr>
 <tr><td>titan</td><td>J48</td><td>0.0865</td><td>0.2092</td><td>99.1435</td><td>2849</td><td>137</td><td>0.977</td><td>0.028</td><td>0.933</td></tr>
 <tr><td>titan</td><td>RandomForest</td><td>0.0695</td><td>0.2021</td><td>79.6121</td><td>2816</td><td>170</td><td>0.97</td><td>0.254</td><td>0.938</td></tr>
 <tr><td>velocity</td><td>NaiveBayes</td><td>0.3767</td><td>0.5658</td><td>75.3796</td><td>270</td><td>155</td><td>0.517</td><td>0.707</td><td>0.61</td></tr>
 <tr><td>velocity</td><td>NaiveBayesMultinomial</td><td>0.418</td><td>0.633</td><td>83.6288</td><td>243</td><td>182</td><td>0.545</td><td>0.596</td><td>0.57</td></tr>
 <tr><td>velocity</td><td>Logistic</td><td>0.3857</td><td>0.4541</td><td>77.1661</td><td>284</td><td>141</td><td>0.665</td><td>0.671</td><td>0.668</td></tr>
 <tr><td>velocity</td><td>SGD</td><td>0.3176</td><td>0.5636</td><td>63.5559</td><td>290</td><td>135</td><td>0.67</td><td>0.694</td><td>0.682</td></tr>
 <tr><td>velocity</td><td>SimpleLogistic</td><td>0.4057</td><td>0.4503</td><td>81.1726</td><td>299</td><td>126</td><td>0.69</td><td>0.716</td><td>0.703</td></tr>
 <tr><td>velocity</td><td>SMO</td><td>0.2941</td><td>0.5423</td><td>58.848</td><td>300</td><td>125</td><td>0.697</td><td>0.714</td><td>0.705</td></tr>
 <tr><td>velocity</td><td>VotedPerceptron</td><td>0.4314</td><td>0.6554</td><td>86.3162</td><td>243</td><td>182</td><td>0.543</td><td>0.597</td><td>0.569</td></tr>
 <tr><td>velocity</td><td>DecisonTable</td><td>0.4224</td><td>0.4675</td><td>84.5178</td><td>287</td><td>138</td><td>0.679</td><td>0.671</td><td>0.675</td></tr>
 <tr><td>velocity</td><td>OneR</td><td>0.4706</td><td>0.686</td><td>94.1568</td><td>225</td><td>200</td><td>0.535</td><td>0.524</td><td>0.529</td></tr>
 <tr><td>velocity</td><td>PART</td><td>0.3867</td><td>0.475</td><td>77.3648</td><td>274</td><td>151</td><td>0.625</td><td>0.662</td><td>0.643</td></tr>
 <tr><td>velocity</td><td>J48</td><td>0.3824</td><td>0.4745</td><td>76.5074</td><td>283</td><td>142</td><td>0.626</td><td>0.698</td><td>0.661</td></tr>
 <tr><td>velocity</td><td>RandomForest</td><td>0.3832</td><td>0.4735</td><td>76.6797</td><td>293</td><td>132</td><td>0.704</td><td>0.673</td><td>0.689</td></tr>
 <tr><td>xalan</td><td>NaiveBayes</td><td>0.3732</td><td>0.4806</td><td>79.7703</td><td>1815</td><td>926</td><td>0.721</td><td>0.572</td><td>0.665</td></tr>
 <tr><td>xalan</td><td>NaiveBayesMultinomial</td><td>0.3782</td><td>0.6129</td><td>80.8362</td><td>1708</td><td>1033</td><td>0.697</td><td>0.502</td><td>0.624</td></tr>
 <tr><td>xalan</td><td>Logistic</td><td>0.3718</td><td>0.4314</td><td>79.4591</td><td>1993</td><td>748</td><td>0.81</td><td>0.516</td><td>0.7</td></tr>
 <tr><td>xalan</td><td>SGD</td><td>0.2718</td><td>0.5213</td><td>58.0914</td><td>1996</td><td>745</td><td>0.812</td><td>0.506</td><td>0.698</td></tr>
 <tr><td>xalan</td><td>SimpleLogistic</td><td>0.3774</td><td>0.4329</td><td>80.6555</td><td>1991</td><td>750</td><td>0.81</td><td>0.512</td><td>0.699</td></tr>
 <tr><td>xalan</td><td>SMO</td><td>0.2729</td><td>0.5224</td><td>58.3253</td><td>1993</td><td>748</td><td>0.813</td><td>0.499</td><td>0.695</td></tr>
 <tr><td>xalan</td><td>VotedPerceptron</td><td>0.355</td><td>0.5957</td><td>75.8683</td><td>1768</td><td>973</td><td>0.738</td><td>0.45</td><td>0.63</td></tr>
 <tr><td>xalan</td><td>DecisonTable</td><td>0.3457</td><td>0.4171</td><td>73.8953</td><td>2013</td><td>728</td><td>0.813</td><td>0.542</td><td>0.712</td></tr>
 <tr><td>xalan</td><td>OneR</td><td>0.3302</td><td>0.5746</td><td>70.5674</td><td>1836</td><td>905</td><td>0.758</td><td>0.479</td><td>0.654</td></tr>
 <tr><td>xalan</td><td>PART</td><td>0.2641</td><td>0.3866</td><td>56.4509</td><td>2100</td><td>641</td><td>0.826</td><td>0.645</td><td>0.758</td></tr>
 <tr><td>xalan</td><td>J48</td><td>0.2307</td><td>0.3874</td><td>49.3105</td><td>2209</td><td>532</td><td>0.852</td><td>0.717</td><td>0.802</td></tr>
 <tr><td>xalan</td><td>RandomForest</td><td>0.2542</td><td>0.3821</td><td>54.3382</td><td>2132</td><td>609</td><td>0.826</td><td>0.694</td><td>0.776</td></tr>
 <tr><td>xerces</td><td>NaiveBayes</td><td>0.1997</td><td>0.433</td><td>76.8415</td><td>526</td><td>128</td><td>0.22</td><td>0.888</td><td>0.786</td></tr>
 <tr><td>xerces</td><td>NaiveBayesMultinomial</td><td>0.3846</td><td>0.6143</td><td>147.995</td><td>405</td><td>249</td><td>0.248</td><td>0.745</td><td>0.669</td></tr>
 <tr><td>xerces</td><td>Logistic</td><td>0.2468</td><td>0.3594</td><td>94.9647</td><td>551</td><td>103</td><td>0.104</td><td>0.914</td><td>0.79</td></tr>
 <tr><td>xerces</td><td>SGD</td><td>0.159</td><td>0.3988</td><td>61.1933</td><td>550</td><td>104</td><td>0</td><td>0.914</td><td>0.774</td></tr>
 <tr><td>xerces</td><td>SimpleLogistic</td><td>0.2695</td><td>0.3595</td><td>103.7007</td><td>554</td><td>100</td><td>0.057</td><td>0.917</td><td>0.785</td></tr>
 <tr><td>xerces</td><td>SMO</td><td>0.1529</td><td>0.391</td><td>58.8397</td><td>554</td><td>100</td><td>?</td><td>0.917</td><td>?</td></tr>
 <tr><td>xerces</td><td>VotedPerceptron</td><td>0.1667</td><td>0.4082</td><td>64.1353</td><td>545</td><td>109</td><td>0.018</td><td>0.909</td><td>0.773</td></tr>
 <tr><td>xerces</td><td>DecisonTable</td><td>0.019</td><td>0.912</td><td>0.775</td><td>548</td><td>106</td><td>0.019</td><td>0.912</td><td>0.775</td></tr>
 <tr><td>xerces</td><td>OneR</td><td>0.1575</td><td>0.3969</td><td>60.6049</td><td>551</td><td>103</td><td>0.226</td><td>0.912</td><td>0.807</td></tr>
 <tr><td>xerces</td><td>PART</td><td>0.22</td><td>0.3694</td><td>84.6511</td><td>551</td><td>103</td><td>0.214</td><td>0.912</td><td>0.806</td></tr>
 <tr><td>xerces</td><td>J48</td><td>0.227</td><td>0.3752</td><td>87.3508</td><td>553</td><td>101</td><td>0.252</td><td>0.914</td><td>0.813</td></tr>
 <tr><td>xerces</td><td>RandomForest</td><td>0.1902</td><td>0.3278</td><td>73.1824</td><td>551</td><td>103</td><td>0.36</td><td>0.91</td><td>0.826</td></tr>
</tbody></table>
