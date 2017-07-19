# LearnGit

using: <a href="http://learngitbranching.js.org/">http://learngitbranching.js.org/</a>

1. initial commit
2. git commit
3. git checkout master
4. git merge
5. git rebase rebaseBranch
6. git rebase master

## Commands
<table>
	<tr>
		<td>git commit -m &lt;message&gt;</td>
		<td>commit with message</td>
	</tr>
	<tr>
		<td>git branch &lt;branch&gt;</td>
		<td>create new branch</td>
	</tr>
	<tr>
		<td>git checkout &lt;branch&gt;</td>
		<td>checkout &lt;branch&gt;</td>
	</tr>
	<tr>
		<td>git checkout -b &lt;branch&gt;</td>
		<td>create new branch & checkout</td>
	</tr>
	<tr>
		<td>git merge &lt;branch&gt;</td>
		<td>merge current branch with &lt;branch&gt;</td>
	</tr>
	<tr>
		<td>git branch -d &lt;branch&gt;</td>
		<td>remove local branch &lt;branch&gt;</td>
	</tr>
	<tr>
		<td>gir rebase &lt;branch&gt;</td>
		<td>copy current branch to &lt;branch&gt; and forwards to it with current branch creating a linear history</td>
	</tr>
	<tr>
		<td>git log --graph</td>
		<td>git tree view in CLI</td>
	</tr>
	<tr>
		<td>git checkout &lt;branch&gt;^</td>
		<td>move up one commit from &lt;branch&gt;</td>
	</tr>
	<tr>
		<td>git checkout &lt;branch&gt;~&lt;num&gt;</td>
		<td>move &lt;num&gt; amount of commit from &lt;branch&gt;</td>
	</tr>
	<tr>
		<td>git branch -f &lt;branch&gt; &lt;ref&gt;</td>
		<td>force move &lt;branch&gt; to &lt;ref&gt;</td>
	</tr>
	<tr>
		<td>git remote add origin &lt;link&gt;</td>
		<td>add remote repository named origin</td>
	</tr>
	<tr>
		<td>git push -u origin &lt;branch&gt;</td>
		<td>pushed branch to origin, -u flag adds upstream (tracking) reference<br> <a href="https://stackoverflow.com/questions/18867824/what-does-the-u-flag-mean-in-git-push-u-origin-master">source</a></td>
	</tr>
	<tr>
		<td>git reset &lt;ref&gt;</td>
		<td>reset current branch to &lt;ref&gt;</td>
	</tr>
	<tr>
		<td>git revert &lt;ref&gt;</td>
		<td>creates a commit on current branch that reverts the commit specified by &lt;ref&gt; by applying the invers diff</td>
	</tr>
</table>
