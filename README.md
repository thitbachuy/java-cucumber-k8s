run CMD:
mvn clean verify -Dcucumber.filter.tags=@Tiki -Dbrowser=chrome -DexecutingEnv=test -DtestedEnv=uat -Dplatform=desktop
