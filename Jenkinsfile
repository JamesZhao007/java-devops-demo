pipline{
    //全部的CICD流程都需要在这里定义

    //任何一个代理可用就立即执行
    agent any

    //定义一些环境信息


    //定义流水线的加工流程
    stages{
        //流水线的所有阶段
        //1. 拉取代码
        //2. 编译
        stage('Compiling') {
            steps {
            //"Things to do"
                echo "Compiling..."
            }

        }
        //3. 测试
        stage('Testing') {
            steps {
                echo "Testing..."

            }

        }

        //4. 打包
        stage('Packing') {
            steps {

                echo "Packing..."
            }
        }

        //5. 部署
        stage('Deploying') {
                echo "Deploying..."
        }

    }

}
