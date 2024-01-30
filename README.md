# Winter CS Camp

This is a winter cs camp held in National Chengchi University on 2024/1/31 ~ 2024/2/2. The main purpose is to let the students who are interested in computer science know about what you should have to learn before you choose computer science as your major.

## 💻 設備需求

| Computers | Pre-installed softwares |
| --------- | ----------------------- |
| Windows   | Powershell or CMD       |
| Mac       | Iterm2                  |

## 📣 Schedule

Schedule's link [here](https://docs.google.com/document/d/11QHqGS9etAwiPgg4OhzGZhMZ6HjQMVGupI8I3ZCp3ac/edit)

## 📘 講義

### 📅 第一天「人與電腦的協作、Unix commands and Shell Script」

#### 📎 人與電腦的協作

- Slides's link [here](https://docs.google.com/presentation/d/1mMqcRotUqBH4X1Jyjz_BD4xcPibSxdonCQ933J3eQd8/edit#slide=id.p)

- 課程內容所需之套件

  - **字型下載**: [MesloLGS NF Regular](https://www.google.com/url?q=https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%2520NF%2520Regular.ttf&sa=D&source=editors&ust=1704195459976407&usg=AOvVaw1ZqnwQ0ZB2yCDr8pLKZ51D)
  - **Iterm2**: [下載連結](https://iterm2.com)
  - **Brew**: [下載連結](https://brew.sh)
  - **upload**: [上傳設計圖](https://docs.google.com/presentation/d/19UVVNFsg4vdvqkoa3aU9ZaJx5RfCF5RlEOnXATT9eso/edit#slide=id.p)
- 安裝 Oh-my-zsh

  ```shell
  wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh
  sh install.sh
  ```

- 安裝 Power10k

  ```shell
  git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
  sh install.sh
  ```
