/**
 * LeetCode：3.无重复字符的最长子串
 * Description：给定一个字符串 s ，请你找出其中不含有重复字符的 最长子串 的长度。
 * 示例 1:
 * 输入: s = "abcabcbb"
 * 输出: 3
 * 解释: 因为无重复字符的最长子串是 "abc"，所以其长度为 3。
 * Solution：遇到子串问题可联想到滑动窗口；
 * 右指针遇到已有字符或右边界前向右移动；左指针在右指针停止移动后向右移动一位
 * 每次左指针移动后，要删除最左的字符在Set中的存放内容
 */

 echo "# putTest" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/YoloYao/putTest.git
git push -u origin main


git remote add origin https://github.com/YoloYao/putTest.git
git branch -M main
git push -u origin main