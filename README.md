# 健行科技大學資訊工程學系進階資安滲透實驗室Ansible劇本及環境

## 這是啥
這是給健行科技大學資訊工程學系進階資安滲透實驗室**專用**的Ansible Playbooks  
由現行系統建置者[星月なるこ](https://naruko.studio/member/naruko_reality)設計

## 這有啥功能
- [ping](playbooks/ping.yml)：用於測試連線使用，如使用[Web UI](https://ansible.d717.uch)為整點全自動執行，如有斷線將會傳送通知至[Telegram](https://web.telegram.org/k/#-4143622304)

## 該怎麼用
首先  
找你的上一任管理員交接完整SOP並設置為新管理員帳號  
接下來停用原管理員(如你是由系統建置者本人親自交接請跳過這步驟，原因是他要負責在系統完全死機時進行重設作業，不想出Trouble時無法被救援別停用)  
最後  
如有遠端管理需求請找系統建置者加入VPN(請先自行下載[Tailscale](https://tailscale.com/download))