# LearnGit

using: <a href="http://learngitbranching.js.org/">http://learngitbranching.js.org/</a><br>
sandbox: <a href="http://learngitbranching.js.org/?NODEMO">http://learngitbranching.js.org/?NODEMO</a>

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
		<td>git push origin -d &lt;branch&gt;</td>
		<td>remove remote branch &lt;branch&gt;</td>
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
	<tr>
		<td>git cherry-pick &lt;ref1&gt; &lt;ref2&gt;</td>
		<td>copy &lt;ref1&gt; and &lt;ref2&gt; on top of the current branch</td>
	</tr>
	<tr>
		<td>git describe &lt;ref&gt;</td>
		<td><i>&lt;tag&gt;_&lt;numCommits&gt;_g&lt;hash&gt;</i>: Describes the closest ancestor tag in history, numCommits is how many commits away that tag is, and &lt;hash&gt; is the hash of the commit being described.</td>
	</tr>
	<tr>
		<td>git pull</td>
		<td>git fetch & git merge</td>
	</tr>
	<tr>
		<td>git pull --rebase</td>
		<td>git fetch & git rebase</td>
	</tr>
	<tr>
		<td>git checkout -b &lt;branch&gt; &lt;remote&gt;/&lt;remoteBranch&gt;</td>
		<td>checkout new branch that's tracking selected remote branch</td>
	</tr>
	<tr>
		<td>git branch -u &lt;remote&gt;/&lt;remoteBranch&gt; &lt;branch&gt;</td>
		<td>setting the tracking on &lt;branch&gt; to &lt;origin&gt;/&lt;remoteBranch&gt;</td>
	</tr>
	<tr>
		<td>git push &lt;remote&gt; &lt;place&gt;</td>
		<td>push &lt;place&gt; to origin, no matter where you are checked out</td>
	</tr>
	<tr>
		<td>git push &lt;remote&gt; &lt;from&gt;:&lt;to&gt;</td>
		<td>push &lt;from&gt; to remote on the &lt;to&gt; branch</td>
	</tr>
	<tr>
		<td>git fetch &lt;remote&gt; &lt;from&gt;:&lt;to&gt;</td>
		<td>fetch &lt;from&gt; from the remote to the &lt;to&gt; branch</td>
	</tr>
	<tr>
		<td>git push &lt;remote&gt; :&lt;remoteBranch&gt;</td>
		<td>technicly we are pushing nothing onto &lt;remoteBranch&gt; and thats equals to deleting that remote branch from the &lt;remote&gt;</td>
	</tr>
	<tr>
		<td>git fetch &lt;remote&gt; :&lt;branch&gt;</td>
		<td>fetching nothing from origin to a non existing branch will create a new branch where we stand</td>
	</tr>
	<tr>
		<td>git pull &lt;remote&gt; &lt;from&gt;:&lt;to&gt;</td>
		<td>git fetch &lt;remote&gt; &lt;from&gt;:&lt;to&gt;; git merge &lt;to&gt;</td>
	</tr>
	<tr>
		<td>git pull &lt;remote&gt; &lt;branch&gt;</td>
		<td>git fetch &lt;remote&gt; &lt;branch&gt;; git merge &lt;remote&gt;/&lt;branch&gt;</td>
	</tr>
	<!--tr>
		<td></td>
		<td></td>
	</tr-->
</table>
