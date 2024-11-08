import org.foo.*

PipelineConfiguration pl = new PipelineConfiguration()

// def commit = bat(returnStdout: true, script: 'git log -1 --oneline').trim()

// String commitMsg = ''

// List commitMsgPre = commit.split(' ')

// for (int i = 1; i < commitMsgPre.size(); i++) {
//     commitMsg += commitMsgPre[i] + ' '
// }

// echo "Commit message: ${commitMsg}"

if (env.BRANCH_NAME == 'main') {
    echo 'Running on main branch'
}

mainPipeline(pl)
