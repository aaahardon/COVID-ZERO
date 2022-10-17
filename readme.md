# 中南大学nCov健康打卡脚本

**注意**：本代码使用Github-Actions定时运行，坚持清零政策，无需部署在服务器。

## 声明

项目用于学习交流，仅用于各项无异常时打卡，如有身体不适等情况还请自行如实打卡！

## 使用

1. Fork本项目到你的仓库
   
2. 设置Secrets
   
    从Github中进入刚刚fork到你的个人账号下的本项目，依次点击上栏 【Setting】->【Security】->【Secrets】->【Actions】
    
    点击【New repository secrets】 按钮新建：

   * USERNAME：中南大学学工号

   * PASSWORD：信息门户密码

3. 启动定时打卡

    点击上栏【Actions】。选中 workflow ，点击【Run workflow】按钮。

4. 查看运行情况

    打开Actions页面，此时在workflows中应该出现了正在运行的工作流。
    
    当手动运行时会马上进行一次打卡，以后将会默认在每天的00:25左右进行打卡（Github定时任务会有20分钟左右的延时）

## 异常处理

如果当天未打卡成功，会抛出异常，Github Action会向您发送一封邮件，所以您无需担心打卡是否成功。

## 修改打卡时间

打开项目中的/.github/workflows/healthy.yml文件，修改corn中的值，注意使用UTC时间。 

# Dynamic zero-COVID protects lives, economy
*Country to keep optimizing measures, balance epidemic control and growth*

China's dynamic zero-COVID strategy remains the most economical and scientific approach to tackling the disease as the pandemic continues to spread across the globe and bring fresh risks, a senior health official said on Wednesday.

Chang Jile, deputy director of the National Administration of Disease Prevention and Control, said that the dynamic zero-COVID approach aims to promptly detect new infections and rein in the spread at the lowest cost and within the shortest possible time.

"The strategy guarantees normal production and the safety of people across the country, and also ensures stable supply chains," he said during a news conference held by the Publicity Department of the Central Committee of the Communist Party of China.

In response to a question on whether the strategy is at odds with the country's economic advancement, Chang said the pandemic is still at a high level, with new variants emerging and knowledge of the novel coronavirus growing.

"We must strengthen our determination … keep optimizing virus control measures based on the latest situation and balance our disease containment policies with the development of society and the economy," he said.

In addition to its effective response to the COVID-19 disease, Chang said China has also significantly improved its capability to deal with other health emergencies that emerged in the past decade, such as H7N9 and Middle East respiratory syndrome. The country has also contributed to the global fight against Ebola.

"China has established the world's largest online reporting system for contagious disease outbreaks and acute public health events," he said.

According to Chang, it now takes less than four hours for localities to report a public health emergency, and the country is able to identify 300 types of pathogens within 72 hours.

"We have also set up a risk evaluation system for public health emergencies and 59 national teams devoted to coping with such incidents."

He said China will focus on handling its COVID-19 epidemic, while improving its ability to cope with emergencies to safeguard the health of the people.
