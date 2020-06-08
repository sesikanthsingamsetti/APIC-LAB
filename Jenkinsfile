pipeline{
agent any
tools{
	ant 'ANT_LOCAL'
}
stages{
stage("Mock"){
steps{
echo 'test'
sh 'ant -v'
}
}
}
}
