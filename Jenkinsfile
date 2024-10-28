import org.foo.*

PipelineConfiguration pl = new PipelineConfiguration()

if (env.BRANCH_NAME == 'main') {
    echo 'Running on main branch'
    pl.branchName = 'main'

    mainPipeline(pl)
}
else {
    echo 'Running on develop branch'
    pl.branchName = 'develop'

    developPipeline(pl)
}