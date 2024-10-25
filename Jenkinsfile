@Library('JenkinsSandboxLibrary') _
import com.org.foo.*

def pl = new PipelineConfiguration()

if (env.BRANCH_NAME == 'main') {
    echo 'Running on main branch'
}

pipeline(pl)
