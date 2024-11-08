import org.foo.*

PipelineConfiguration pl = new PipelineConfiguration()

node {
    def commit = bat(returnStdout: true, script: 'git log -1 --oneline').trim()

    String commitMsg = commit.substring( commit.indexOf(' ') ).trim()

    echo "Commit message: ${commitMsg}"
}

if (env.BRANCH_NAME == 'main') {
    echo 'Running on main branch'
}

mainPipeline(pl)
