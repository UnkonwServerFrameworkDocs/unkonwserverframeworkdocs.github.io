<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://mirror.mengze2.cn/proxy/github.com/EarthDLL.png',
    name: 'EarthDLL',
    title: '维护/编辑/主程序/领导者',
    links: [
      { icon: 'github', link: 'https://github.com/EarthDLL' },
    ]
  },
  {
    avatar: 'https://mirror.mengze2.cn/proxy/github.com/qcbby.png',
    name: 'qcbby',
    title: '维护/编辑',
    links: [
      { icon: 'github', link: 'https://github.com/qcbby' },
    ]
  },
  {
    avatar: 'https://mirror.mengze2.cn/proxy/github.com/MengZe2l.png',
    name: 'MengZe2l',
    title: '维护/编辑',
    links: [
      { icon: 'github', link: 'https://github.com/MengZe2l' },
      { icon: 'x', link: 'https://x.com/MengZe2' }
    ]
  },
  {
    avatar: 'https://mirror.mengze2.cn/proxy/github.com/YYTZ666.png',
    name: 'YYTZ666',
    title: '编辑',
    links: [
      { icon: 'github', link: 'https://github.com/YYTZ666' },
    ]
  },
]
</script>

# 官网维护团队

我们的文档/官网维护团队

<VPTeamMembers size="small" :members="members" />