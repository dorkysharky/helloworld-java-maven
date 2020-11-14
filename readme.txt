
This dad;ad;s 
This is my fixsssed for DevOpsSchool.com....Fix for Taskggggg 55555  HON-1dsdasdasdaadas6666666
For any questions - Please email me at DevOps@RajeshKumar.gxyz/
# this isddd a fix og sdfljflld fjldsfjdsjfkdl;sdasdasdasd
# ========================NEXUS==============================

<distributionManagement>
	<repository>
		<id>tata</id>
		<name>Internal Releases</name>
		<url>http://13.127.163.182:8081/repository/scmgalaxy/</url>
	</repository>
 
	<snapshotRepository>
		<id>tata</id>
		<name>Internal Releases</name>
		<url>http://52.66.106.91:8081/nexus/content/repositories/snapshot/</url>
	</snapshotRepository>

</distributionManagement>


===============ARTIFACTORY=================
<distributionManagement>
	<repository>
		<id>rajesh</id>
		<name>Internal Releases</name>
		<url>http://192.168.100.9:8081/artifactory/dhlall/</url>
	</repository>
 
	<snapshotRepository>
		<id>rajesh</id>
		<name>Internal Releases</name>
		<url>http://192.168.100.9:8081/artifactory/dhlall/</url>
	</snapshotRepository>

</distributionManagement>

=====================SETTING.XML=================================
   <server>
		<id>rajesh</id>
		<username>rajesh-user</username>
		<password>rajesh-user123</password>
</server>

=======================Setting.xml with Artifactory Setup======================
<mirror>
      <id>central</id>
      <name>Maven Repository Manager running on repo.mycompany.com</name>
      <url>http://13.127.94.210:8081/artifactory/list/group/</url>
      <mirrorOf>*</mirrorOf>
    </mirror>
    
    

